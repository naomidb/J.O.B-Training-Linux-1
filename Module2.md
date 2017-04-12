# J.O.B-Training-System Information Commands Assignment

## You will now practice the system information commands in linux using the previously cloned repo that will track your work.

### Exercise 1 Date
In a terminal window practice the date command which is call date.
1) In your terminal type the command ```man date``` and read the documentation related to the date command
2) Type the command date and note the format and information displayed on your screen
3) Change directory to the root of your file system by typing ```cd /``` and then type ```pwd```
4) Change directory to the users directory by typing ```cd /users``` and then type ```pwd```
5) Type the command ```cd $repodir``` to return to your exercise directory

### Exercise 2 Present Working Directory
In a terminal window practice the present working directory command which is call pwd.
1) In your terminal type the command pwd
  a) note that the terminal displays the current directory that you are working in
2) Document your current directory by typing the command ```pwd > pwd.txt```
3) Change directory to the root of your file system by typing ```cd /``` and then type ```pwd```
4) Change directory to the users directory by typing ```cd /users``` and then type ```pwd```
5) Type the command ```cd $repodir``` to return to your exercise directory

### Exercise 3 Change Directory
In a terminal window practice the change directory command which is called cd. 
1) Type the command ```man cd``` and read the documentation related to the manual for the change directory command
  a) press the Q button to quit out of the manual
2) Change directory to the root of your file system by typing ```cd /```
3) Change directory to your Linux home drive by typing ```cd ~```
4) Type the command ```cd $repodir``` to return to your exercise directory
4) Verify that you are in your exercise directory by typing ```pwd > pwd.txt```

### Exercise 4 List Directory Content
In a terminal window practice the list directory content command which is called ls.
1) Type the command ```man ls``` and read the manual for the command
  a) pay particular attention to the options -l -t -r -a -h
2) List the current contents of the directory you are located in by typing ```ls```
3) List the current contents of the directory you are located by file creation date by typing ```ls -ltr```
  a) note that the files in your current directory are listed by date
4) List the current contents of the directory you are located in by listing hidden files by typing ```ls -lah```
  a) note that the you now see more directories such as .git and .DS_Store
5) List hidden files in the current directory by creation date by typing ```ls -latr```
  a) note that you see all files plus hidden files sorted by last modified date
6) Type the command ```ls -latr > ls.txt``` to log your work to the file ls.txt for later review

### Exercise 5 Concatenate
In a terminal window practice the concatenate command which is called cat. Concatenate can display any human readable file such as a text file, a comma serperated values file or script.
1) Type the command ```man cat``` and read the manual for the command
2) Display the content of the pwd.txt file to your screen by typing ```cat pwd.txt```
  a) see that the cat file displays on your screen the pwd.txt file you created in the present working directory exercise
3) Type ```cd /``` and then type ```cat users```
  a) note that you receive an error when trying to concatenate users because it is a directory and not a file 
4) Type the command ```cd $repodir``` to return to your exercise directory
4) Type ```echo 'This is a test file' > test.txt``` and then type ```cat test.txt```

### Exercise 6 Execute a Command as another User
In a terminal window practice executing commands as another user by typing sudo. Sudo is a very powerful command that allows you to execute programs on a Linux system that are restricted to specific account with higher elevated rights.
1) Type the command ```man sudo``` and read the manual for the command
2) Type the command ```sudo su -``` and type in your password
  a) note that your terminal now reads root because you have just switched to the root user account. Every command you type is executed as the root user and can be harmful if you are not careful
3) Type the command ```exit``` to return to your regular user account

## Please return to the <a href="https://kevinhanson.github.io/J.O.B.-Jump-On-Board/" target="_blank">Linux Commands Course Website</a> to continue to the next module.