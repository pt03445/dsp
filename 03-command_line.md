# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > * show current working directory path --> pwd     
    * creating a directory --> mkdir <name of the dir>      
    * deleting a directory --> rm -rf <name of the dir>  
    * creating a file using `touch` command --> touch <name of the file>  
    * deleting a file --> rm -rf <name of the file>  
    * renaming a file --> mv <originalNameFile> <NewFileName>  
    * listing hidden files --> ls -lart  
    * copying a file from one directory to another --> cp -r <sourcedirectory/filename> <destinationdirectory>  
     
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> >  `ls` - Command to list directories/files  
     `ls -a` - Command to list files including Hidden files (i.e.) filenames starting with "."  
     `ls -l` - Command to list files with details such as file size, last modified etc  
     `ls -lh` - Command to list files with details such as file size in in human readable format kb/mb/Gb  
     `ls -lah` - Command to list files including hidden files with details such as file size in in human readable format kb/mb/Gb  
     `ls -t`  - Command to list files by sorting them based on the time they were modified  
     `ls -Glp` - Command to list Directories with / and Unix file type with file permissions, file size, last modified etc    

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * find . -name <filename> --> (Command to search a file name)    
    * netstat -a  --> Command to Display all connections and lsitening ports  
    * ps -ef|grep <processname> --> Command to check and display if a specific process is up and running  
    * su --> Command to become a different user (i.e) su root to become root  
    * tail -f <filename> --> Command to follow/trace a file  
    
    

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > * xargs Command in Unix takes the input from stdin and executes any given command over the input.  
    * eg: find . -name "*.c" | xargs rm -rf  
    * In the example above, the command is to find any file name with extension ".C" and remove it. Xargs is taking the input (i.e) all       the files with .C extension and removes them.   


 

