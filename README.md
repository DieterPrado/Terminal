# Termina

### Table of contents

- General info
- Technologies
- Setup
- Commands

------------

### General info

The terminal course is a great introduction in how terminal works. The course teaches a great variety of commands as well as its options and functions. The course cleared up doubts about terminal and was in general a great introduction to how terminal can be manipulated.

------------

### Technologies

The terminal commands are designed to work in Unix enviroments, so for windows users it is needed to install an application that allows the use of linux commands. In this case it was installed and used Ubuntu from Microsoft Store and worked with its terminal.

- **Ubuntu**

------------

### Setup

This project only has commands, so to run this project you only need a Unix based terminal.
- Go to microsoft store.
- Search Ubuntu.
- Install Ubuntu.
------------


### Commands

##### Commands

|  Command | Function  | Command line options (Examples)|
| ------------ | ------------ |
|  cd | Used to change directory. | none |
|  pwd | Shows your current directory location. | pwd -L use PWD from environment, even if it contains symlinks|
|  mkdir | Creates a new directory. | mkdir -v  print a message for each created directory. -m  set file mode (as in chmod), not a=rwx - umask |
|  touch | Creates a new file. | touch -a  change only the access time |
|  cp | Copy. | cp --attributes-only  don't copy the file data, just the attributes |
|  mv | Move and rename files. | mv -f  do not prompt before overwriting |
|  rm | Removes files. | rm -i  prompt before every removal  |
|  rm -r | Used to remove directories. | Forcefully remove |
|  ls | Shows the files of your current location. | ls -l List format |
|  find | Finds a file | find -p Never follow symbolic links |
|  grep | Searches **in** files | grep -c Counts the occurency in a file. grep -i Ignores uppercase or lowercase differences. |
|  ifconfig | Shows the config of the net | ifconfig -v be more verbose for some error conditions |
|  wget | Brings things from internet | wget -b Go to background immediately after startup. |
|  netstat -i  | Shows the devices of the net. | Shows the devices of the net |
|  ping | Checks if a website is working. | ping -b Allow pinging a broadcast address. |
|  tar compress | Compress files. | --- |
|  ps | Shows running processes. | ps -elf To get info about threads: |
|  top |  Shows the processes that are using more resources. | top -v  Show library version and the usage prompt, then quit. |
|  kill | Kills processes. | --- |
|  jobs | Shows all the background processes. | jobs -l Provide more information about each job listed. |
|  fg | Moves a process to foreground. | --- |
|  bg | Moves a process to background . | --- |
|  man | Shows a manual. | man top provides information about top command. You can change top for any other command|
|  alias | Creates an alias for another command. |  |
|  info | Similar to manual but shorter. | --- |
|  whatis | Tells what a command do. | whatis top rovides information about top command. You can change top for any other command.  |
|  xdg-open | Opens text files. | --- |
|  head | Shows the 10 first lines of a text file. | head -q never print headers giving file names | 
|  tail | Shows the 10 last lines of a text file. | tail -v always output headers giving file names |
|  less | Shows all the text file. | less -bn Specifies the amount of buffer space less will use for each file, in units of kilobytes (1024 bytes).  |
|  tree display | Displays all the files like a tree. | --- |
|  cat | Shows the content of a text file. | cat -s suppress repeated empty output lines |
|  && | If the previos command runs it will run the next| --- |
|  ; | Runs synchronized commands. |  --- |





