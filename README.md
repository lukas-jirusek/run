# run: Compiles and runs C code.
### Usage: 
&nbsp;&nbsp;&nbsp;&nbsp;run [[ -s | --silent ][ -h | --help ]] path/to/c/file [arguments for your program]   
#### Compilation:   
&nbsp;&nbsp;&nbsp;&nbsp;Normal mode: g++ -Wall -pedantic -Wextra -O2 main.c   
&nbsp;&nbsp;&nbsp;&nbsp;Silent mode (see Options): g++ -O2 main.c   
    
#### Script creates temporary file called ".temporeryFile.out". This file is automatically deleted.   

#### Options:    
&nbsp;&nbsp;&nbsp;&nbsp;-s | --silent		Disables compilation warnings (-Wall -Wextra -pedantic) and other progress messages.   
&nbsp;&nbsp;&nbsp;&nbsp;-h | --help		Shows help page (what you are seing right now).   
    
#### Bugs:   
&nbsp;&nbsp;&nbsp;&nbsp;Cannot pass arguments used by this script (-h, --help, -s, --silent).   
   
#### Possible problems:   
&nbsp;&nbsp;&nbsp;&nbsp;Not sure if it is capable of passing arguments (did some tests, worked).   
&nbsp;&nbsp;&nbsp;&nbsp;Not sure if it handles C++ code (did some tests, worked).   
&nbsp;&nbsp;&nbsp;&nbsp;Not sure if it handles path to C file properly (did some tests, should work).   
&nbsp;&nbsp;&nbsp;&nbsp;Uses multiple commands, some of those might not be installed on your machine(tput, dirname, basename, g++).   
&nbsp;&nbsp;&nbsp;&nbsp;Other problem may appear at any time.   
