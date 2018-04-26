# Shell
This repository contains code that was used to implement a shell.
It was divided into three phases :
Phase 1 : Implement a basic shell.
Phase 2 : Implement Piping, I/O Redirection, Aliasing and History Feature and a custom editor.
Phase 3 : Implement additional functionality to the shell that is not already available in Linux.

So we implemented 
1. sgown function - 
  It takes two arguments - the directory path and a keyword. Given these two values, it recursively searches all the files and subdirectories within this directory and prints the files in which this keyword occurred along with the count.
Usage - sgown <directory path> <keyword>
2.  ls -z 
  This function lists all regular files of size zero in the current directory.
  Usage : ls -z 
