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

> > `pwd`  show current working directory path  
> > `mkdir`  creating a directory  
> > `rm -r`  deleting a directory  
> > `touch`  create a file  
> > `rm`  deleting a file  
> > `mv`  renaming a file  
> > `ls -a`  listing hidden files  
> > `cp`  copying a file from one directory to another  
> > `cd`  switch to the specified directory  
> > `ls -l`  list files in long format  
> > `mv`  move a file to a different directory  

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

> > `ls`  list files in directory  
> > `ls -a`  list all files in directory, including those that start with a dot (hidden)  
> > `ls -l`  list files in long format  
> > `ls -lh`  list files in long format, with file sizes displayed using human-friendly units  
> > `ls -lah`  list all files in long format, with file sizes displayed using human-friendly units  
> > `ls -t`  list files sorted by timestamp (newest first)  
> > `ls -Glp`  list files in long format, puts / after directory names, and colorizes by file type  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls -r`  list files in reverse order  
> > `ls -R`  list files, including those in subdirectories  
> > `ls -u`  list files, sorted by access time  
> > `ls -d`  lists only directories  
> > `ls -m`  lists files, separated by commas  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` executes commands based on the standard input.  
> > For example, to find .txt files which contain the string "hello", you would use `find -name "*.txt" | xargs grep "hello"`.



