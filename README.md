# run: Compiles and runs C and C++ code.
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
    
#### Script creates temporary file called ```.temporeryFile.out```. This file is automatically deleted.   

#### Options:    
&nbsp;&nbsp;&nbsp;&nbsp;```-s | --silent```&nbsp;&nbsp;Disables compilation warnings (-Wall -Wextra -pedantic) and other progress messages.   
&nbsp;&nbsp;&nbsp;&nbsp;```-h | --help```&nbsp;&nbsp;Shows help page (what you are seing right now).   
&nbsp;&nbsp;&nbsp;&nbsp;```-d | --debug```&nbsp;&nbsp;Compiles and launches gdb. (BETA)   
&nbsp;&nbsp;&nbsp;&nbsp;```-i | --input path/to/file```&nbsp;&nbsp;Inputs contents of your file as standart input into your program.   
&nbsp;&nbsp;&nbsp;&nbsp;```-o | --output```&nbsp;&nbsp;Saves text produced by your program into custom file.   
    
#### Required packages:   
&nbsp;&nbsp;&nbsp;&nbsp;```tput, dirbase, basename, g++(duh), gdb (for debugging)```.   
   
#### Known bugs:   
&nbsp;&nbsp;&nbsp;&nbsp;None known, probably many. Report bugs at https://github.com/lukas-jirusek/run/issues/new.   

#### Author:
&nbsp;&nbsp;&nbsp;&nbsp;Lukáš Jirůšek, [lukas.jirusek33@gmail.com](mailto:lukas.jirusek33@gmail.com)
