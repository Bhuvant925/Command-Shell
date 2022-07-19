# Shell Implentation in C
# This assignment is a component of the operating systems course taught by Dr. Praveen Kumar at VNIT.

# Please read the ReadMe completely before using it and use it at your own risk.

STEP 1: First download the c file and then compile it in your Ubuntu Terminal or any Linux OS  
STEP 2: Then Run it , that's it now your custom command shell starts working.
Note
All mentioned commands without quotes
Don't copy if it is your assignment just read the man pages for commands and try to implement small programs you will learn a lot it is just for reference.
The shell will run an infinite loop (which will only exit with the ‘exit’ command). 

# Brief introduction

The shell will print a prompt that indicate the current working directory followed by ‘$’ character.
The shell doesn't support inline edit of commands and history of commands entered.
Changing directory using cd.

# Incorrect command
An incorrect command format (which your shell is unable to process) will print an error message ‘Shell: Incorrect command’.

# Signal handling
Ignores  ‘Ctrl + C’ and ‘Ctrl + Z’ in main process. When these signals are generated, shell will continue to work and the commands being executed by the shell should respond to these signals.

# Executing multiple commands
The commands separated by ‘&&’ are executed in parallel .
The commands separated by ‘##’ should be executed sequentially. 
Shell will not execute simultaneous use of ‘&&’ and ‘##’. 

# Output redirection
To redirect STDOUT for the commands using ‘>’ symbol. 
simultaneous use of multiple commands and output redirection doesn't work.

# If in case any on entering 'exit' if your shell doesn't exit please clear the screen usign 'clear' then execute 'exit' again and even if the shell doesn't exit then only one way is remaining that is quiting the shell use 'ctrl + \\' .

# Verdict of the Final Code : Passed All Test Cases
