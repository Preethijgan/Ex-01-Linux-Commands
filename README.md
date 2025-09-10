# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

 <img width="745" height="118" alt="image" src="https://github.com/user-attachments/assets/a2098306-437a-4b9d-a79a-ba4b3f6a4a3b" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="410" height="57" alt="image" src="https://github.com/user-attachments/assets/987a8266-1259-4027-9074-ff25a3060f9a" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="730" height="110" alt="image" src="https://github.com/user-attachments/assets/31f1d8c7-6b93-4f41-9c66-39a363d277c1" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="681" height="106" alt="image" src="https://github.com/user-attachments/assets/c1cfab9f-005e-47b6-8dcb-d41c1b2e02a6" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="484" height="131" alt="image" src="https://github.com/user-attachments/assets/95540ef6-b50b-425f-a743-2ecab9747d1a" />



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="725" height="177" alt="image" src="https://github.com/user-attachments/assets/c6b51f76-5790-4837-bdc1-fad0a4430ead" />




 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="638" height="162" alt="image" src="https://github.com/user-attachments/assets/8397cc73-75f5-4ac3-88dc-87506f69d28d" />




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="738" height="50" alt="image" src="https://github.com/user-attachments/assets/ba24c4c7-65bc-4e16-8c2e-08c347e9d030" />



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="776" height="102" alt="image" src="https://github.com/user-attachments/assets/e7486861-10bf-49b6-95f8-e27665c924e0" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="672" height="213" alt="image" src="https://github.com/user-attachments/assets/cf53c797-2a66-42b5-8136-392816e1f524" />


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="727" height="137" alt="image" src="https://github.com/user-attachments/assets/deb200a7-da61-48c9-b8e2-811d38ecef3e" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="482" height="193" alt="image" src="https://github.com/user-attachments/assets/fb2fa877-7836-4736-9e52-653f328dd7e1" />




### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="313" height="212" alt="image" src="https://github.com/user-attachments/assets/44b01f36-c2da-42a5-abf6-9ff2cbf33a24" />



 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="786" height="93" alt="image" src="https://github.com/user-attachments/assets/04ad2774-4fd4-4fdb-87ae-2a2c88f59838" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="448" height="77" alt="image" src="https://github.com/user-attachments/assets/9d7587f1-955e-4f15-9a8d-9942afe030e9" />



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="427" height="147" alt="image" src="https://github.com/user-attachments/assets/43f939ee-1005-4c1a-9110-8575ce7c20da" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="593" height="55" alt="image" src="https://github.com/user-attachments/assets/41e1e133-a4ac-412b-b434-f258aeb016ff" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar -cvf archive.tar file1 file2 

<img width="526" height="90" alt="image" src="https://github.com/user-attachments/assets/9dec61fc-c79d-4a37-91e8-92198743d651" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="663" height="122" alt="image" src="https://github.com/user-attachments/assets/f7f4c099-ed02-4cb7-ab45-a1bc287fb5c0" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
$ hostname -I

<img width="775" height="292" alt="image" src="https://github.com/user-attachments/assets/d4081240-a77b-45c7-9909-baf2afe64cb8" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="752" height="106" alt="image" src="https://github.com/user-attachments/assets/fee598f0-6737-4382-bc31-9f2255cd7dcb" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="648" height="107" alt="image" src="https://github.com/user-attachments/assets/295541c5-abe2-46ee-a79a-a56505b90e89" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="597" height="47" alt="image" src="https://github.com/user-attachments/assets/f9376c5e-80c3-47de-ba4f-7a5a455740bf" />




### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
