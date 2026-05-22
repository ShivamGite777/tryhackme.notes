# Linux Fundamentals

Today I learned:

- pwd = show current folder
- ls = list files
- grep = search text
- nc = Netcat tool

Tools used:
- Linux Terminal
CAT FOR FINDING THE TEXT
tryhackme@linux1:~/Documents$ ls
todo.txt
tryhackme@linux1:~/Documents$ cat todo.txt
Here's something important for me to do later!


Using "find" to find a file with the name of "passwords.txt"
tryhackme@linux1:~$ find -name passwords.txt
./folder1/passwords.txt
tryhackme@linux1:~$


Using "find" to find any file with the extension of ".txt"
tryhackme@linux1:~$ find -name *.txt
./folder1/passwords.txt
./Documents/todo.txt
tryhackme@linux1:~$

GREP
Using "wc" to count the number of entries in "access.log"
tryhackme@linux1:~$ wc -l access.log
244 access.log
tryhackme@linux1:~$



SHELL OPERATOR
Operator "&"
Operator "&&"
Operator ">"
Operator ">>"

& - The "&" shell operator allows us to execute a command and have it run in the background
&&- to make a list of commands to run for example command1 && command2. However, it's worth noting that command2 will only run if command1 was successful.

>-
> Operator
tryhackme@linux1:~$ echo hey > welcome

Using cat to output the "welcome" file
tryhackme@linux1:~$ cat welcome
hey

>> = add content without deleting old content
