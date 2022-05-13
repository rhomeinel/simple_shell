Simple Shell

Repository Description
This repository contains files to simulate basic Unix Shell with its normal commands. 0x16. C- Simple Shell project at ALX Holberton

Learning Objectives
At the end of the project, we should be able to explain the project without the help of Google

General
Who designed and implemented the original Unix operating system
Who wrote the first version of the UNIX shell
Who invented the B programming language (the direct predecessor to the C programming language)
Who is Ken Thompson
How does a shell work
What is a pid and a ppid
How to manipulate the environment of the current process
What is the difference between a function and a system call
How to create processes
What are the three prototypes of main
How does the shell use the PATH to find the programs
How to execute another program with the execve system call
How to suspend the execution of a process until one of its children terminates
What is EOF / “end-of-file”?

Environment
Language: C
Style GuidelineBetty style
OS: Ubuntu 20.04 LTS

Resources
Melissa Medium Blog How a Shell Works
Unix Shell
Thompson Shell
Ken Thompson shell

Description Of Files
man_3_shell
shell.h
main.c

Shell Function Files
FILE	description
1	prompt.c	handles outline of shell's reprompting and executing
2	print_error.c	prints special error messages for certain fails
3	__exit.c	handles if user types exit or exit(value)
4	get_env.c	finds and returns copy of environmental variable
5	env_linked_list.c	prints and creates linked list of envrionmental variables
6	set_unset_env.c	finds environment variable index node, sets and unsets
7	free_double_ptr.c	frees double pointers (user's command, arrays)
8	int_to_string.c	converts int to string to write error messages
9	_execve.c	executes and frees command, then exits program
10	which.c	changes directories
11	_cd.c	finds environment variable index node, sets and unsets
12	get_line.c	reads user's typed input into buffer
13	linked_lists.c	adds and deletes nodes; prints and frees linked list
14	_strcat.c	concatenates two strings
15	_strcmp.c	compares if two strings match
16	_strdup.c	duplicates a string
17	_str_tok.c	tokenizes user's command input and returns array
18	_realloc.c	helper function handles reallocation
19	c_str_tok.c	handles output when shell is called outside of shell
20	_strcpy.c	copies a string

