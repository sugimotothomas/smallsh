# Assignment 3: smallsh (Portfolio Assignment)
 	By: Thomas Sugimoto
 	sugimoth@oregonstate.edu
 	CS 344 Operating Systems Fall 2020
 	11/3/2020
 	smallsh.c

 	A bash-like shell application written in C.
 	- Provides a prompt for running commands
	- Handles blank lines and comments, which are lines beginning 
	  with the # character
	- Provides expansion for the variable $$
	- Executes 3 commands exit, cd, and status via code built into 
	  the shell
	- Executes other commands by creating new processes using a function 
	  from the exec family of functions
	- Supports input and output redirection
	- Supports running commands in foreground and background processes
	- Implements custom handlers for 2 signals, SIGINT and SIGTSTP


## Installation
	To compile and run simply go to the directory with the smallsh.c
	file and run the commands:
		gcc -o smallsh smallsh.c
		./smallsh