---
layout: section
title: CLI Warmup
---
##The Command Line Interface (CLI)

##GUI vs CLI

GUI
: Graphical User Interface

CLI
: Command Line Interface

API
: Application Programming Interface

##Why use the CLI?

1. Great for administration
  - Much greater power and control
2. Great for repetitive/recurring tasks
3. Operating systems already implement many useful programs
	- Take advantage!

##Linux Bash Basics

###Directory Structure

- System root is `/`
- Absolute Path/Relative Path?
- File Permissions/Access

###Linux Bash Basics

Basic Commands

ls
: List files in your directory

pwd
: Print your current path

cd path
: Change context to a different directory

cp path1 path2
: Copy a file

mv path path
: Move or rename a file

rm path
: Unallocate space used by a file

rmdir path
: Delete an empty directory

mkdir path
: Create a new directory

cat path
: Display the contents of a text file

echo string
: Display a string to the screen

grep
: Search for a string within the file system

###Bash Scripting (Hello World)

1. Linux Bash Intermediate, commands:
 - man / info
 - more, less, head, tail
 - grep exercises with c (count), v (inverse), various flags
 - uniq, sort, cut (awk / sed)
 - ps, top, pkill
 - hexdump
 - mount,df, du
 - diff, md5sum

2. Linux Bash Intermediate: Redirection/Piping/Logical Branching

3. Linux Bash Advanced: Environment variables

4. Configuration files
	- /etc
	- hidden home files (starts with `.`)

5. Alternate/Embedded CLIs

Many times, programs will present their own CLI to the user (independent of OS);
often these are called consoles, console-mode, or interpreter-mode

- ftp
- mysql
- sqlite
- netsh
- irc
- PYTHON!!
