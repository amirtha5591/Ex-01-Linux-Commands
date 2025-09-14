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


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="1501" height="652" alt="Screenshot 2025-09-08 101851" src="https://github.com/user-attachments/assets/188fdd2b-2c29-44b4-a978-0a2060c9adda" />



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="814" height="401" alt="Screenshot 2025-09-08 103753" src="https://github.com/user-attachments/assets/31a4fbc0-5a6b-4642-891a-7a990f72ae2f" />
 
 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<img width="312" height="127" alt="image" src="https://github.com/user-attachments/assets/5cbaac4a-888e-48c2-a201-de4ab92b6426" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="593" height="136" alt="image" src="https://github.com/user-attachments/assets/94642dd1-b4eb-4970-b8ad-8fd5a1bddc22" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<img width="296" height="118" alt="image" src="https://github.com/user-attachments/assets/5e91d8bf-0b8c-4113-8c68-6cd8bb4c2af9" />
 
 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="332" height="62" alt="image" src="https://github.com/user-attachments/assets/4d2ddf8f-36de-4378-a2a2-bf4d16b58407" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="301" height="107" alt="image" src="https://github.com/user-attachments/assets/0e0bcb21-43c5-4627-bc65-4ab0a909ecb7" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="293" height="96" alt="image" src="https://github.com/user-attachments/assets/bf0955a4-501a-4dd7-b3f9-eb91721bc166" />
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="1916" height="111" alt="image" src="https://github.com/user-attachments/assets/e9c34718-d536-46b1-864a-f3b5e82dab3e" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="306" height="77" alt="image" src="https://github.com/user-attachments/assets/dff28630-3541-4a76-b31d-2b178248aaa0" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="382" height="82" alt="image" src="https://github.com/user-attachments/assets/48c963da-8696-4835-9a45-2ffda75f1fe6" />
### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="318" height="117" alt="image" src="https://github.com/user-attachments/assets/464ad510-ccec-468e-a791-7bb8ecca68dc" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
 tar xvzf file.tar *.c
$<img width="847" height="91" alt="image" src="https://github.com/user-attachments/assets/55c6f3d0-e5c2-4cac-b935-4e735453d336" />
 
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="355" height="105" alt="image" src="https://github.com/user-attachments/assets/24d86764-2c99-4f54-b009-03e3b3261593" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="515" height="90" alt="image" src="https://github.com/user-attachments/assets/3d9c2c62-0acd-4e1c-9b0c-529208f8bcda" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="853" height="422" alt="image" src="https://github.com/user-attachments/assets/2254cc98-4312-45ef-a114-f08374426a76" />
### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 <img width="285" height="112" alt="image" src="https://github.com/user-attachments/assets/9d23c9f6-5616-42be-9729-85031409eb25" />
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="525" height="113" alt="image" src="https://github.com/user-attachments/assets/cd9fe49c-3861-478d-ad00-6466836b9277" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<img width="303" height="117" alt="image" src="https://github.com/user-attachments/assets/5b4c2564-e3a9-4799-b2fc-cb489d75dcce" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="308" height="71" alt="image" src="https://github.com/user-attachments/assets/97200281-6928-43f5-9ad1-34cd35d1a243" />
 
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="646" height="731" alt="image" src="https://github.com/user-attachments/assets/15064bb0-1bf3-46c6-807a-dcc47862c02b" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="341" height="147" alt="image" src="https://github.com/user-attachments/assets/cc6d2707-deab-4a6b-a8ab-b7d28cbdc78b" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="945" height="340" alt="image" src="https://github.com/user-attachments/assets/49530f2c-6048-4d18-94e8-8ef70c50e696" />
### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<img width="345" height="76" alt="image" src="https://github.com/user-attachments/assets/b42cd549-ddc7-4b4f-a183-b905488ef0a0" />

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
