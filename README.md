# rshell #

The purpose of this program is to execute a simple command shell named rshell which is very identical to the bash shell. 

* It first prints out a command prompt with the username and hostname. 

* It then reads in commands and executes them to an extent.

* Rshell works with comments in the command line and also multple flags.

## Add Ons ##

### ls ###

This program also contains an almost fully working implementation of ls comparable to bash ls. You can use the flags "-a", "-l", "-R", or any combination of the three on any directory on your hard drive. 

### cp ###

Rshell contains a fully working implementation of cp comparable to bash cp. It works the same as cp where there are two arguments needed and one optional argument. There are three different implementations of cp in the cp.cpp file. With the thrid argument, you can choose if you want to run all three and output their runtimes or run the fastest.

#BUGS#

##rshell##

This program has a few bugs. 

* It is not working when you input multiple commands. 

* Rshell only works when you have one command with flags, e.g. "ls -a" , "ls -a1", etc.

* It does not work with && or || or ; connectors for the command line.

##ls##

This implementation of ls has a few known bugs.

* The combination of all three flags "-alR", "-laR", etc. is not working.

* When you want to use ls on a file, you get an error that you cannot open a directory.

* Flags: "-Rl", "-R", are not working.
