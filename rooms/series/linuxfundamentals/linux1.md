# Linux Fundamentals 1


## A bit of background on linux
#### Research: What year was the first release of a Linux operating system? | Answer: 1991

## Running Your First few Commands
#### If we wanted to output the text "TryHackMe", what would our command be? | Answer: echo tryhackme

## Interacting With the Filesystem!
#### On the Linux machine that you deploy, how many folders are there? | Answer: 4 (use 'ls' to display the folders)
#### Which directory contains a file? | Answer: folder4 (use 'cd' to enter a directory, and 'ls' to find files)
#### What is the contents of this file? | Answer: Hello World! (use 'cat' to find the contents of the file)
#### Use the cd command to navigate to this file and find out the new current working directory. What is the path? | Answer: home/tryhackme/folder4 ('pwd')

## Searching for Files
#### Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag? | Answer: THM{ACCESS} (grep "THM" access.log)

## An Introduction to Shell Operators
#### If we wanted to run a command in the background, what operator would we want to use? | Answer: & ( see the table above )
#### If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be? | Answer: echo passwords > password123
#### Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be | Answer: echo tryhackme && passwords
#### Now use the deployed Linux machine to put these into practice | Answer:
