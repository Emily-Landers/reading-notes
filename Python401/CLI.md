# Practice in the Terminal

## The Command Line 

- Linux has a graphical user interface that is comparable to the GUI's on other systems like Windows and OSX.
- A command line(AKA Terminal) is a text based interface to the system in which you can enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
    - Line 1 presents us with a prompt 
    - Lines 2 - 5 are output from running the command.
    - Line 6 presents us with a prompt again.
- Within a terminal you have what is known as a shell. Which is a part of the operating system that defines how the terminal will behave and look after running (or executing) commands.

## Basic Navigation 

- **pwd** stands for Print Working Directory. It tells you what your current or present working directory is.
- **ls** is short for list and it will give us our current location in the directory
- There are 2 types of paths, absolute and relative.
- Absolute paths specify a location
- Relative paths specify a location
- The root directory is at the very top of the structure
- use **cd** with a location argument to change directories 

## More About Files 

- **file** helps you obtain information about what type of file a file or directory is.
- **ls -a** will list the contents of a directory, including hidden files.
- Everything is a file under Linux including directories
- Linux is an extensionless system, files are not required to have extensions, but they can
- Linux is case sensitive

## Manual Pages 

- You can easily look stuff up in the man pages.
- ```man <command>``` to look up the manual page for a particular command.
- ``` man -k <search term> ``` to do a keyword search for all manual pages containing the given search term.
- ``` /<term> ``` within a manual page, perform a search for 'term'
- ```n``` after performing a search within a manual page, select the next found item.

## File Manipulation

- ```mkdir``` Make Directory - ie. Create a directory.
- ```rmdir``` Remove Directory - ie. Delete a directory.
- ```touch``` Create a blank file.
- ```cp``` Copy - ie. Copy a file or directory.
- ```mv``` Move - ie. Move a file or directory (can also be used to rename).
- ```rm``` Remove - ie. Delete a file.
- The Linux command line does not have an undo feature. Perform destructive actions carefully.

