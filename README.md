# Ex-01-Linux-Commands
## NAME : SUDHAKARAN S
## REG NO:212222220051
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

![1](https://github.com/user-attachments/assets/12eca13e-6c55-43c7-9306-32f30db1cf9b)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![2](https://github.com/user-attachments/assets/601ccc62-5eac-4325-b2e6-ef5e2f40629e)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![3](https://github.com/user-attachments/assets/6320b9f5-ecbf-407e-8c33-6932b5adbc7b)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![4](https://github.com/user-attachments/assets/1bfb8331-ef69-4083-b036-f616947ccce0)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![5](https://github.com/user-attachments/assets/17ed06a3-83df-4215-a570-6aa9da63751d)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![6](https://github.com/user-attachments/assets/9085a4e5-41a0-4b89-ab3a-9f9156a86ccf)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![7](https://github.com/user-attachments/assets/38500428-4534-4247-b56d-0b23b73c8ed6)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![8](https://github.com/user-attachments/assets/3ac04521-5d53-4af3-8bc1-a56172ed06e5)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![9](https://github.com/user-attachments/assets/18855a0c-19f6-4fd0-9d46-7105abfe1467)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![10](https://github.com/user-attachments/assets/0c048afe-1300-4af6-9b8e-d971eb883b62)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![11](https://github.com/user-attachments/assets/93d662a5-2617-42b1-ad27-5589c696f5b1)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![12](https://github.com/user-attachments/assets/13950d64-e4bc-4d89-823d-2f4eaef97ac2)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![13](https://github.com/user-attachments/assets/0dbd73ce-00dc-4682-a2d5-9f4f64f7fd8b)


### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![14](https://github.com/user-attachments/assets/271bd113-094c-45e3-8ab3-55710729849f)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![15](https://github.com/user-attachments/assets/b1d70ae4-a9b3-43ab-ae4c-dc0bb765cc78)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![16](https://github.com/user-attachments/assets/56bccda7-1cb2-4057-8d08-02c4a9957a48)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![19](https://github.com/user-attachments/assets/83dd6667-4762-4122-a451-c4666a026956)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![20](https://github.com/user-attachments/assets/661f6446-ac1c-4e8f-aabc-98dc357b1f30)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/49eba749-432d-4781-b840-cef388ea1cca)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/3ed1a386-4acd-45e0-988e-5c8f91724e91)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/702d984b-18ab-41be-99ce-8f12092d5164)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/94201a8c-442d-4d50-a950-6150c6b7c806)


### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/f70d268d-3053-4257-9d7d-87836bf9b435)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/db06dbad-b3de-40e2-b4a6-7bc6347c78f0)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/63f3333e-bbff-4fb1-8e49-ec4bbf8f3888)


### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/Mena-Rossini/Ex-01-Linux-Commands/assets/102855266/4df9a6ff-ec1e-4929-adfe-32c909a90e4a)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
