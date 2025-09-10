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
<img width="688" height="69" alt="image" src="https://github.com/user-attachments/assets/b27a71e5-abd8-4d77-8493-2d0a87c16b70" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="550" height="47" alt="image" src="https://github.com/user-attachments/assets/2194c6a9-fa48-484d-8fd0-e84e33cc3a30" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="640" height="44" alt="image" src="https://github.com/user-attachments/assets/cd3722d1-17bc-4b6a-94ac-dd8240cf1c54" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="660" height="45" alt="image" src="https://github.com/user-attachments/assets/a17c194d-28ee-45f1-8360-cef61d2af1c5" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="679" height="41" alt="image" src="https://github.com/user-attachments/assets/0e63ca13-4271-4108-bf74-bd6a24d27d6a" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="655" height="240" alt="image" src="https://github.com/user-attachments/assets/f30fd2ed-6afc-42fa-857e-503fded5f5d5" />


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<img width="707" height="155" alt="image" src="https://github.com/user-attachments/assets/be23acb7-68ed-4c65-9234-2310e07c939e" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="670" height="36" alt="image" src="https://github.com/user-attachments/assets/f37e1835-a5e6-4257-acfe-e60378d38ecf" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="865" height="47" alt="image" src="https://github.com/user-attachments/assets/59b1c78b-d567-4967-90cd-0a4d47777bf2" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<img width="408" height="44" alt="image" src="https://github.com/user-attachments/assets/7835a80d-ab03-4783-93eb-ca46e21171fb" />
<img width="351" height="46" alt="image" src="https://github.com/user-attachments/assets/29bd9c57-f727-41a7-9a21-f210ed9215e0" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="437" height="65" alt="image" src="https://github.com/user-attachments/assets/3f9cf283-0f18-4415-9e49-9ec351f993c4" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="706" height="469" alt="image" src="https://github.com/user-attachments/assets/b996d06b-92cf-4128-b93e-2ff54df7e0aa" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="645" height="154" alt="image" src="https://github.com/user-attachments/assets/95897b13-966c-4402-bee9-8030b32a8d8c" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="848" height="78" alt="image" src="https://github.com/user-attachments/assets/4ecff7a6-9c56-4630-9924-e1f48902f522" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="588" height="156" alt="image" src="https://github.com/user-attachments/assets/2c8de452-d9a2-445a-ad5e-69438ad5d2cc" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="380" height="151" alt="image" src="https://github.com/user-attachments/assets/d77614e5-8f2a-423e-a20e-b0154d40259a" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="424" height="68" alt="image" src="https://github.com/user-attachments/assets/85ea8317-5808-46a9-84cc-c6c38a5baa98" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 <img width="426" height="57" alt="image" src="https://github.com/user-attachments/assets/865e359f-7728-4986-87ae-ec7f784fc314" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="364" height="86" alt="image" src="https://github.com/user-attachments/assets/15844318-2879-4a8a-bb99-959c17239888" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="342" height="22" alt="image" src="https://github.com/user-attachments/assets/aa4e1651-e080-4e88-a703-36a21512dee6" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="858" height="209" alt="image" src="https://github.com/user-attachments/assets/f70bc929-c8b1-4e7b-88bb-0030c12f2c9b" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="377" height="70" alt="image" src="https://github.com/user-attachments/assets/95a217be-c8fd-4707-8ae5-b02a585628a8" />
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="376" height="71" alt="image" src="https://github.com/user-attachments/assets/ad57f53a-f7b9-431f-b3bb-a7277ec0d73d" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<img width="363" height="56" alt="image" src="https://github.com/user-attachments/assets/7f4d456d-f6f5-4c3c-b794-85127680e3f8" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="362" height="146" alt="image" src="https://github.com/user-attachments/assets/87640b63-4ab7-4607-9081-aeadd3b4b97c" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="280" height="99" alt="image" src="https://github.com/user-attachments/assets/04823818-74f9-4a16-87c1-c334a2aff171" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="314" height="38" alt="image" src="https://github.com/user-attachments/assets/b5a65f76-c188-431b-98e3-c882be0b520b" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="515" height="27" alt="image" src="https://github.com/user-attachments/assets/5a618084-41d6-49e3-b5c4-f6cee242d33c" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="571" height="134" alt="image" src="https://github.com/user-attachments/assets/eaaad6c4-a83d-4ca7-8a8f-632daa3b33a1" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<img width="499" height="43" alt="image" src="https://github.com/user-attachments/assets/2fd47bd4-fa3f-4026-86cb-39d3ec893aaf" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
