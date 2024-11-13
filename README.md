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


![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/14313087-1efa-4ac2-9f64-f6cd0b93b145)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/324ded1a-70f3-4150-bcb2-b4a9d6ad1fd6)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/78b77518-86db-41df-a320-aa463fb9c546)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/c01cbdc7-8259-49ad-b5f5-c00346e4ec78)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/19fe100a-f515-4866-9573-6879fa277ef3)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/eab5eaf1-5752-4910-b8fd-e417b3980fbb)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/914e3c44-960e-4951-b314-e1ecebadcc51)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/7a544174-c379-4e25-aa5c-b63fbc43e69c)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/5eb89bea-c625-431f-82c6-349496ca4ea5)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/faf3e9d5-2ad0-4318-9180-ee839e7ad46a)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/29b4bc14-34c2-45c9-9a58-0d6de4c7114a)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/89e68de2-8aef-4415-a6b7-b1d03eed9c71)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/6b9ea3ba-a82b-45ac-93fc-f4e94fbd6e61)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/698d86b6-121f-49e8-b792-37dddf2bc0b3)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/f630a18b-99d1-4c1b-887b-e0dec6c95d3e)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/a8edd60a-3083-4f91-97b1-03794f9ce777)

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
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/72cb380a-d600-477f-b3b5-51168408c952)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/c6330223-124c-4c9b-a69d-d8c18dce6984)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/cbb69a2a-f209-4133-8f35-7da29b171e5d)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/6aa29466-366e-43b9-8dbb-f9427b3371d6)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/49166e6e-6546-4905-955b-208136ee701a)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/d3b9c042-76ac-49e6-8921-20593a2aa984)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/a96f0eb7-6475-4ea0-952e-2b81a56dc6ba)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/9f44ad79-6697-4c16-bc7b-f10141b80747)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/00e6a379-3469-48a8-adde-f2abb5498be6)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/1808charitha/Ex-01-Linux-Commands/assets/132996838/c04c158b-9559-4007-b1f1-37c47f2f97aa)



### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
