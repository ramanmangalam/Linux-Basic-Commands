# Linux-Basic-Commands

These are the Basics commands we are using in the Linux 

So first of all, what is Linux?

Linux came from a Unix family, Linux is a Open-Source software operating system,which linux Torvalds developed in September 1991.

Basic-Commands

1) touch - Touch command is use to create empty files,we can't write data in a file,can't edit or save file 
Syntax:- touch filename
eg)-touch firstfile
To create Multiple Files- touch secondfile thridfile fourthfile
TO create Number of Files - touch firstfile{1..10}

2) ls - It Shows available files and directory list in the present working directory.
syntax:- ls
 
3) vi/vim- Vi and Vim are both command-line text editors for Linux used to edit text-based files, and both allow the creation of files with content or data. The difference is that Vim offers additional features compared to Vi.
And there are 3 modes in write a file in the vim/vi
1) Command mode-Here we cant write anything,to write need press ESC
2) Insert mode-Here we write the content,then press ESC :
3) Execution mode- Here we can save or quit from the file.for save-:wq! and for quite- :q!

Syntax:- vi/vim filename
eg)-vi/vim firstfile

4) mkdir - It mainly used for to create a Single directory in the Linux
Syntax:- mkdir directoryname
eg):- mkdir firstdirectory
To create multiple directory- mkdir seconddirectory thirddirectory fourthdirectory
To create number of  directory- mkdir /firstdirectory{1..10}
For create directory path (directory inside directory)- mkdir -p/dev/firstdirectory/firstfile

5) man - man command in Linux displays the manual for any command run in the terminal

6) rm - rm command in Linx use to delete a file .
Syntax:- rm firstfile 

7) rm-r - rm-r command in Linux use to delete a directory
Syntax:- rm -r firstdirectory 
