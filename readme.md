A shell script to locate executable files based only on the user's PATH environment variable. This script takes a list of file names from the command line and determines which would be executed had these names been given as commands.


The script by default will find only the first occurrence of the "file". The -a option will display all occurrences. If the file is not found, the script will report the following message:

<command> not found

usage: whichhunt [-a] command ....

Example:

$ whichhunt ls

/bin/ls
