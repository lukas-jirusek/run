Compilation:
	  Normal mode: g++ -Wall -pedantic -Wextra -O2 main.c
	  Silent mode (see Options): g++ -O2 main.c
    
Script creates temporary file called ".temporeryFile.out". This file is automatically deleted.

Options: 
	  -s | --silent		Disables compilation warnings (-Wall -Wextra -pedantic) and other progress messages.
	  -h | --help		Shows help page (what you are seing right now).
    
Bugs:
	  Cannot pass arguments used by this script (-h, --help, -s, --silent).
   
Possible problems:
	  Not sure if it is capable of passing arguments (did some tests, worked).
	  Not sure if it handles C++ code (did some tests, worked).
	  Not sure if it handles path to C file properly (did some tests, should work).
	  Uses multiple commands, some of those might not be installed on your machine(tput, dirname, basename, g++).
	  Other problem may appear at any time.
