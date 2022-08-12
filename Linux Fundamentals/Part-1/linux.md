# Introduction
Just like Windows, iOS and MacOS, Linux is just another operating system and one of the most popular in the world powering smart cars, android devices, supercomputers, home appliances, enterprise servers, and more.

# Basic Commands
``` bash
echo "Hello World"
# print Hello World

whoami
# Find out what user we're currently logged in as!

clear
# Clear the terminal

ls
# Listing

cd
# Change directory

cat filename.extension
# Concatenate(To display contents of a file.)

pwd
# Print Working Directory

# Instead of using cd and ls commands to know the files, the find command can also be used for searching files
find -name passwords.txt
# Search for a file named passwords.txt

find -name *.txt
# * => Wildcard
# Search for all .txt files

grep "string-to-search" filename.extension
# This command allows searching the contents of a file for specific values
```

# Operators
Some important operators in linux are:
* & operator:
    * allows us to execute commands in the background
    * Example: copying a large file

* && operator:
    * make a list of commands to run simultaneously
    * Example: **command1 && command2**
    * command2 will only run if command1 was successful

* > operator:
    * known as an output redirector
    * take the output from a command executed and send that output to somewhere else(usually, to some file.)
    * Example: echo hey > welcome saves the string hey to a file named welcome

* >> operator:
    * similar to output redirector
    * if there is already a file with the same name, then the output of the command is appended at the end of the file(The file is not overwritten.)

