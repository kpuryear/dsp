# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)

| Action | Command |
| --- | ---- |
| Show current directory | pwd |
| Create a directory | mkdir <directory_name> |
| Deleting a directory | rm -R -i <directory_name> |
| Creating a file using touch command | touch <file_name.extension> |
| Deleting a file |rm <file_name> |
| Listing hidden files | ls -a |
| Copy a file from one directory to another | cp -r <original_path>/ <new_path> |
| Rename a file | rm <bad_name.extension> <good_name.extension> |
| Opening a nested directory | cd <directory_name> |
| Move up a folder | cd .. |

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

| Input | What it does |
| ----| ---- |
| `ls` | lists files found in a given directory |
| `ls -a` | lists all files (including hidden ones!) |
| `ls -l` | lists all files with their characteristics |
| `ls -lh` | lists long format with readable file size |
| `ls -lah` | lists all visible and hidden files, permissions, number, owner, group, size, date last modified. Ordered by filename. |
| `ls -t` | lists files sorted by output time |
| `ls -Glp` | lists visible files, permissions, number, owner, group, size, time of last modification, and name |


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

| Input | What it does |
| ---- | ---- |
| `ls -r` | Displays files in reverse order |
| `ls -R` | Displays subdirectories as well |
| `ls -q` | Displays all nonprinting characters as ? |
| `ls -u` | Displays files by the file access time |
| `ls -1` | Displays each entry on a line | 

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` is a function that allows us to search through a directory and find files with a certain name or extension. 
</br>
Here is an example:</br>
`xargs find -name`</br>
`"*.txt"`</br>
`"*.log"`</br>
This command will return any files with the extensions .txt or .log in our current directory.

 

