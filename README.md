# run: Compiles and executes C and C++ code.
## Link:   
#### [Link to code](https://github.com/lukas-jirusek/run/blob/master/run)   
#### [RAW](https://raw.githubusercontent.com/lukas-jirusek/run/master/run)
### Usage: 
```
run [ OPTIONS ] path/to/c/file [ARGUMENTS]   
```
### Installation:
Paste following into your terminal:
```
curl https://raw.githubusercontent.com/lukas-jirusek/run/master/run > ~/.run
sudo mv ~/.run /usr/local/bin/run
chmod a+x /usr/local/bin/run   
```
And you should be ready to go!   
   
   
### Help page: 
#### Compilation:   
&nbsp;&nbsp;&nbsp;&nbsp;Normal mode: ```g++ -Wall -pedantic -Wextra -O2 main.c   ```   
&nbsp;&nbsp;&nbsp;&nbsp;Silent mode (see Options): ```g++ -O2 main.c   ```

#### Options:    
&nbsp;&nbsp;&nbsp;&nbsp;```-s | --silent```&nbsp;&nbsp;Disables compilation warnings (-Wall -Wextra -pedantic) and other progress messages.   
&nbsp;&nbsp;&nbsp;&nbsp;```-h | --help```&nbsp;&nbsp;Shows help page (what you are seing right now).   
&nbsp;&nbsp;&nbsp;&nbsp;```-d | --debug```&nbsp;&nbsp;Compiles and launches gdb. (BETA)   
&nbsp;&nbsp;&nbsp;&nbsp;```-i | --input path/to/file```&nbsp;&nbsp;Inputs contents of chosen file as standart input into your program.   
&nbsp;&nbsp;&nbsp;&nbsp;```-o | --output path/to/output```&nbsp;&nbsp;Saves text produced by your program into custom file.   
&nbsp;&nbsp;&nbsp;&nbsp;```-c | --compare file/to/compare```&nbsp;&nbsp;Compares output of your program with chosen file.   
&nbsp;&nbsp;&nbsp;&nbsp;```-e | --examples```&nbsp;&nbsp;Shows examples how to use this script.   
&nbsp;&nbsp;&nbsp;&nbsp;```-v | --version```&nbsp;&nbsp;Show version of this script, g++, gdb, realpath and diff.   
    
#### Required packages:   
&nbsp;&nbsp;&nbsp;&nbsp;```tput, realpath g++(duh), gdb (for debugging), colordiff or diff (for comparing)```.   
   
#### Known bugs:   
&nbsp;&nbsp;&nbsp;&nbsp;None known, probably many. Report bugs at https://github.com/lukas-jirusek/run/issues/new.   

#### Author:
&nbsp;&nbsp;&nbsp;&nbsp;Lukáš Jirůšek, [lukas.jirusek33@gmail.com](mailto:lukas.jirusek33@gmail.com)
