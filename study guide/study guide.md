---
Name: Sabrina mahmud
class: cis106
semester: spring 22
---

### Study Guide For Final Spring 2022 

#### List of Commands

* date 
Display the current time and date.
![q1](q1.1.png)

* uname
Displays information about your system.

* du

* free
Displays the amount of free memory.

echo
* apt
for advanced package tool- is set of tools for managing Debian packages.


* pwd 
Displays the current working directory where you are currently working.
![q1](q1.3.png)

* cd
![q1](q1.4.png)
change the current working directory. in other words, moves you around.
How to use it : cd + destination 

* ls 
is used for listing the content of a given directory or the file directory itself.

* tree
* man
Man manual  pages are documentation files that describe Linux shell commands, executable programs, systems,calls,special files,and so forth.
man pages are not step by step guides ,but instead quick reference


* mkdir 
is used for creating a single directory or multiple directories.

* touch
is used for creating files 


* rm
remove files 
rm by default does not removes directories.T o remove a directory use rm with the -r option.

* cp
copies files/directories from
source to a destination 
the cp command uses the same structure as the mv command 


* mv
moves and renames directories.

* stat
a data structure that contains all the information about a file except the file name and content.
* Example 
stat script.sh 

* Wildcards (*,?,[])
the main wildcard is a star ,or asterisk(*) character.
A star alone matches anything and nothing and matches any number of characters
* Example  ls *.txt wil match all files that end in txt regardless of the size of the file name .

* Brace expansion
{} is not a wildcard but another feature of bash that allows you to generate 
rabbitry string to use with commands.

* cat
the cat command is use for displaying the content of a file .
cat is short for concatenate which is the command intended.
* Usage 
cat + option +file(s) to display


* head
the head command displays the top N number of lines of a given file by default it prints the first 10 line  If more than one file name is provided then data from each file is proceeded by its file name.

* tail
the head command displays the top N number of lines of a given file by default it prints the first 10 line  If more than one file name is provided then data from each file is proceeded by its file name.


* cut
the / etc/passwd contains one lne for each user account, with seven fields delimited by colons(:)

* tr 
used for translating or deleting or characters from standard output.


* paste
is use for joining files horizontally in columns 

* wc
the wc is used for printing the number of lines characters and bytes in a file.

* grep 
is used to search text in given file. grep works line by line basis.
* Usage 
grep + option search criteria + file(s)


Saving the output of a command
command output + > +file



