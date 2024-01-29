# Tools of the Trade: Linux and SQL

## Module 3 - Linux Commands in Bash Shell

### Learnings

- The command line
- Navigating and managing the file system
- Authenticating and authorizing users
- Accessing resources


### Linux commands via the Bash Shell

**Security analysts**

- Work with server logs
- Navigate, manage, and analyze files remotely
- Verify and configure users and group access
- Give authorization and set file permissions

**Bash**

The default shell in most Linux distributions

**Command**

An instruction telling the computer to do something

**Argument (Linux)**

Specific information needed by a command


### Core commands for navigation and reading files

**Filesystem Hierarchy Standard (FHS)**

The component of the Linux OS that organizes data

**Root directory**

The highest-level directory in Linux

**`pwd`**

Prints the working directory onto the screen

**`ls`**

Displays the names of files and directories in the current working directory

**`cd`**

Navigated between directories

**`cat`**

Displays the content of a file

**`head`**

Displays just the beginning of a file, by default 10 lines

**`tail`**

Displays just the ending of a file, by default 10 lines


### Find what you need with Linux

**`grep`**

Searches a specified file and returns all lines in the file containing a specified string

**`|` (piping)**

Sends the standard output of one command as standard input to another command for further processing


### Create and modify directories and files

**`mkdir`**

Creates a new directory

**`rmdir`**

Removes, or deletes, a directory

**`touch`**

Create a new file

**`rm`**

Removes, or deletes, a file

**`mv`**

Moves a file or directory to a new location

**`cp`**

Copies a file or directory into a new location


### Add and delete users

**Root user (or superuser)**

A user with elevated privileges to modify the system 

**Problems with logging in as root**

- Security risks
- Irreversible mistakes
- Accountability

**`sudo`**

Temporarily grants elevated permissions to specific users

**`useradd`**

Adds a user to the system

**`userdel`**

Deletes a user from the system


### Manual in Linux Shell

**`man`** 

Display information on other commands and how they work

**`whatis`**

Displays a description of a command on a single line

**`apropos`**

Searches the manul page description for a specified string


