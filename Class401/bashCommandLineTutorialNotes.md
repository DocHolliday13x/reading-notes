# Bash Command Line Tutorial Notes

## The Command Line

1. What is it?
   - The command line is an interface that allows you to talk directly to your computer through a terminal.
2. How does it work?
   - The command line is a text interface for your computer. It's a program that takes in commands, which it passes on to the computer's operating system to run.
3. How do I get one?
   - On Mac, you can find the Terminal program in Applications -> Utilities. On Linux, you can use the built-in Terminal. On Windows, you'll probably want to use the Git Bash terminal that comes with the Git software. You can also use the Windows Subsystem for Linux, which provides a Linux terminal environment within Windows.

## Basic Navigation

1. Key Takeaways -
   - `pwd` - Print Working Directory
   - `ls` - List the contents of a directory
   - `cd` - Change Directories
   - `~` - Home Directory
   - `.` - Current Directory
   - `..` - Parent Directory
   - `file` - Obtain information about what type of file a file or directory is.
   - `ls -a` - List the contents of a directory, including hidden files.
   - `ls -l` - List the contents of a directory in long format, with extra details.
   - `ls -t` - List the contents of a directory sorted by the time they were last modified.
   - `ls -R` - List the contents of a directory and all subdirectories.
   - `ls -F` - List the contents of a directory and show a `/` after the names of directories.
   - `ls -S` - List the contents of a directory and sort by file size.
   - `ls -h` - List the contents of a directory and show file sizes in human readable format.
   - `ls -r` - List the contents of a directory in reverse order.
   - `ls -1` - List the contents of a directory on a single line.
   - Relative Path: A file or directory location relative to where we currently are in the file system.
   - Absolute Path: A file or directory location in relation to the root of the file system.

## More About Files

1. Key Takeaways -
   - Under the hood, everything is a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc.
   - Linux is an extensionless system. Files can have any extension they like or none at all.
     - file.exe - An executable file, or program.
     - file.txt - A plain text file.
     - file.png, file.gif, file.jpg - An image.
   - Linux is case sensitive. Beware of silly typos.
   - Spaces in names are perfectly acceptable but we need to handle them differently.
   - Quotes are used to group together multiple words/treat them as one item.
   - Escape characters (backslash) are used to treat the next character as a regular character.
   - Hidden files and directories are preceded by a `.` (dot) and won't be displayed unless you ask for them.

## Manual Pages

1. What are they?
   - Manual pages are a set of pages that explain every program on your computer. They are the best way to learn about commands.
2. Searching:
   - `man -k` - Search for commands containing a particular keyword.
   - `man -f` - Display the manual pages containing a particular keyword.
3. More On Running Commands:
   - A lot of being proficient at Linux is knowing which command line options we should use to modify the behaviour of our commands to suit our needs. A lot of these have both a long hand and short hand version. eg. Above you will notice that to list all directory entries (including hidden files) we can use the option -a or --all (remember from last section what files and directories beginning with a . are?). The long hand is really just a more human readable form. You may use either, they both do the same thing. One advantage of using long hand is that it can be easier for you to remember what your commands are doing. One advantage of using shorthand is that you can chain multiple together easier.
4. Summary:
    - `man` - Show the manual for a command.
    - `man -k` - Search for a command.
    - `man -f` - Display the commands related to a keyword.
    - `man -h` - Show help for a command.
    - `man <command>` - Show the manual for a command.
    - `man -k <keyword>` - Search for commands containing a keyword.
    - `/<term>` - Within a manual page, perfrom a search for 'term'.
    - `n` - Move the cursor to the next occurence of the search term.

## File Manipulation

1. How to make files:
   - mkdir - Make a directory.
   - touch - Make a file.
2. How to remove files:
   - rmdir - Remove a directory.
   - rm - Remove a file.
3. How to rename files:
   - we can use mv to rename files. It can also be used to move files from one directory to another.
4. How to copy files:
   - cp - Copy a file.
5. How to move files and directories:
   - mv - Move a file.
6. Summary:
   - mkdir - Make a directory.
   - rmdir - Remove a directory.
   - touch - Make a file.
   - cp - Copy a file.
   - mv - Move a file/rename a file.
   - rm - Remove a file.

## Cheat Sheet

Quick References:

1. Basic Navigation:
   - `pwd` - Print Working Directory - ie. Where are we currently.
   - `ls` - List the contents of a directory.
   - `cd` - Change Directories.
   - Path - A description of where a file or directory is located in the file system.
   - Absolute Path - A path that describes where a file or directory is in relation to the root of the file system.
   - Relative Path - A path that describes where a file or directory is in relation to where we currently are in the file system.
   - `~` - The tilde symbol is a shortcut for your home directory.
   - `.` - The dot symbol is a reference to your current directory.
   - `..` - The double dot symbol is a reference to the parent directory.
   - TAB completion - The ability to type the first few characters of a file or directory name and press tab to have the rest filled in for you.

2. More About Files:
   - `file` - Obtain information about what type of file a file or directory is.
   - Spaces in names - Put whole path quotes or a backslash in front of spaces.
   - Hidden files and directories - Hidden files and directories are preceded by a `.` (dot) and won't be displayed unless you ask for them.

3. Manual Pages:
   - `man` - Show the manual for a command.
   - `man -k` - Search for a command.
   - `q` - exits the manual page.

4. File Manipulation:
   - `mkdir` - Make a directory.
   - `rmdir` - Remove a directory.
   - `touch` - Make a file.
   - `cp` - Copy a file.
   - `mv` - Move a file/rename a file.
   - `rm` - Remove a file.
