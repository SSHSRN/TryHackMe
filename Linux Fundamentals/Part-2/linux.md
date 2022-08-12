# SSH:
* Secure SHell
* common means of connecting to and interacting with the command line of a remote Linux machine
* protocol between devices in an encrypted form
* Using cryptography, input we send in a human-readable format is encrypted for travelling over a network and is then unencrypted once it reaches the remote machine
* SSH allows us to execute commands on another device remotely

## Flags and Switches:
* A majority of commands allow for arguments to be provided
* These arguments are identified by a hyphen and a certain keyword known as flags or switches
* When using a command, unless otherwise specified, it will perform its default behaviour
* Example: ls lists the contents of the working directory
    * However, hidden files are not shown
    * We can use flags and switches to extend the behaviour of commands
    * However, after using the -a argument (short for --all), we can also see the hidden files and folders
    * Files and folders with "." are hidden files.

## Help:
* Usually, commands that accept flags and swwitches will also have a --help option
* This option will list the possible options that the command accepts, provide a brief description and example of how to use it
* This option is, in fact, a formatted output of what is called the man page (short for manual), which contains documentation for Linux commands and applications

## MAN(ual) page:
* The manual pages are a great source of information for both system commands and applications available on both a Linux machine, which is accessible on the machine itself and online
* To access this documentation, we can use the man command and then provide the command we want to read the documentation for. 
* Example: **man ls**

## FileSystem Interaction:
``` bash
touch filename.extension
# Create a new file "filename.extension"

mkdir foldername
# Create a new folder "foldername"

rm filename.extension
# Remove (Delete) "filename.extension"

rm -R foldername
# Remove (Delete) "foldername"

cp file1.extension file2.extension
# Copies the content of "file1.extension" to "file2.extension"

mv file1.extension file2.extension
# Moves the content of "file1.extension" to "file2.extension"
# mv can also be used to rename a file or folder

# In linux, it is not mandatory for a file to have an extension
file filename
# Display the type of content inside the file "filename"
```