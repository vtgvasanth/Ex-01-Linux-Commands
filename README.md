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

![Screenshot 2023-10-20 085452](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/3231afbf-31db-4eae-9a4e-4857a5334d96)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![Screenshot 2023-10-20 085659](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/631389db-7c2d-4c6e-a34a-7c0c94fb90cd)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![Screenshot 2023-10-20 085747](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/5e7a2a7b-328c-4039-99d6-9e44206e2745)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![Screenshot 2023-10-20 085840](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/177a203a-ecbb-4878-add2-f42f2c29b123)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![Screenshot 2023-10-20 085914](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/58beef2c-2e0d-4d14-b5a6-d806c8b1d81b)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![Screenshot 2023-10-20 085952](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/5e2417aa-589d-4e21-88f5-ce1094000915)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![Screenshot 2023-10-20 090027](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/3ff740d0-e6ae-45c8-8a2f-adfa976c137e)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![Screenshot 2023-10-20 090059](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/5069c51f-844c-4014-bc32-d3578300be05)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![Screenshot 2023-10-20 090135](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/a724d2d7-7f88-4466-a38a-163184ec8e5e)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![Screenshot 2023-10-20 090200](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/c39b1a17-0db8-41c2-8245-0be78b0896e2)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![Screenshot 2023-10-20 090217](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/aebdd71f-fac2-424a-a9eb-f3f01bacea0d)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![Screenshot 2023-10-20 090238](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/b4b2154c-5cb5-4465-a280-b7e0259ab4ab)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![Screenshot 2023-10-20 090256](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/5c80ce32-8725-4ff4-bbed-ff34b6680fec)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![Screenshot 2023-10-20 090311](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/902fe9df-1bd6-40ff-b992-639e0f43ee86)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![Screenshot 2023-10-20 090423](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/3da3e361-6faa-4e2a-a9e9-4a4156b88c4f)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![Screenshot 2023-10-20 090423](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/87c336fd-0ecb-4739-b165-d7092fa07b9d)

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
![Screenshot 2023-10-20 090440](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/07179d3e-faee-4c09-9160-80fdb741e086)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![Screenshot 2023-10-20 090450](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/3ce8dbb6-1e80-47a8-b8df-514a616a5050)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![Screenshot 2023-10-20 090505](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/c60cf2a4-6d7a-495a-8757-c8d08e71bdfa)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![Screenshot 2023-10-20 090450](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/51685b5e-4919-49b5-88c5-dab75ce47a48)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![Screenshot 2023-10-20 090604](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/34193d41-b475-4e7b-9898-89efb5e396b3)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![Screenshot 2023-10-20 090618](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/77af1242-e096-482c-8993-3fd2023fb5fe)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![Screenshot 2023-10-20 090629](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/26ad8350-1d47-475e-8ac1-1153165138d2)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![Screenshot 2023-10-20 090640](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/73da0d46-242a-41f9-bb8f-ebc4cf38c809)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![Screenshot 2023-10-20 090648](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/ae81e9ab-c8e6-4b74-8d27-f9124c790cfa)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![Screenshot 2023-10-20 090702](https://github.com/DEEPAK22003907/Ex-01-Linux-Commands/assets/119404520/8282ffef-252d-4665-a5a2-52c1a15ad6ca)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
