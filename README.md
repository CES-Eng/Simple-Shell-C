# Simple-Shell-C
A simple shell written in C for CS210 coursework. 


## Features implemented
Supports UNIX Commands, history invocations, aliases (with recursive aliases)


## Example Usable functions
```
getpath
setpath
cd
alias
unalias
history
```

## Installation (Linux users can skip to Step 3)
Step 1:<br />
Enable Bash on Ubuntu on Windows 10. [Useful guide](https://developerinsider.co/stepwise-guide-to-enable-windows-10-subsystem-for-linux/) 

Step 2:<br />
Install gcc compiler in Windows 10 Bash by opening bash and running:<br />
```apt-get install gcc```

Step 3:<br />
Download .c file 

Step 4:<br />
Using bash, cd to the directory containing the .c file<br />
```cd C:\Users\USERNAME\Downloads```

Step 5:<br />
Compile program with gcc command and create executable file called simpleshell:<br />
```gcc shell.c -o simpleshell```

Step 6:<br />
Execute program with command:<br />
```./simpleshell```
