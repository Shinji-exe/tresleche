# Terminal & Git

## From point A to B

So you have your terminal open and ready which is amazing. Now you're probably asking how do I go from directory to directory or folder to folder? Why would I use the terminal over regular file explorer. Well in the field this is a lot faster and more reliable using the terminal like rapid creations of files and folders, killing a task application, or other complex means like user permissions.

**cd**(change directory) 
Using this two letter command **cd**, we can change where we want to navigate in the terminal

example: cd Documents/LTCA

This example basically says I want enter the Documents folder, and after that enter the Learn to Code Academy folder(LTCA).

Notice how we have to enter the **Documents** folder first before going to the **LTCA** folder.

Just like your file explorer it will show this
home>user>Documents>LTCA or home/user/Documents/LTCA.

Samething with the terminal because it's about a hierarchy.

**cd~**
This command basically takes you to home. Takes you to the very beginning like the start of the terminal which can be used anywhere for quick escape back to the origin(That was weird lol).

**cd ..**
This command instead of going all the way back home, you go back a directory.

example: Documents/LTCA => cd ..(going back to Documents folder, and leaving LTCA) => Documents

Notice how we went back a directory and no longer in the LTCA folder.

**pwd** (Print Working Directory)
Print Working Directory is basically asking the terminal like "Hey where am I?" This can be used anywhere to find your current location.

example pwd => /home/user
This shows that I am at the user directory

## Making a folder

This is how you make a folder in the terminal/cli/bash
* **mkdir**(Meaning make directory or make a folder) command

## Making a file
Similar to the **mkdir** that makes folders, we can make files, but with a different terminal command. 

example: mkdir myFolder (this makes a folder/directory called **myFolder**)

* **touch**(Making a file which can be .html, .css, .js, .txt , etc)
example: touch index.html (this makes a file with the name **index** and the file type of **.html**)

## Combining the commands

You can make multiple folders and/or multiple files in on line
*mkdir **folder1 folder2 folder3** (This makes multiple folders in one line)
*touch **index.html style.css script.js** (This makes multiple files in one line)

## List and details

To show a list of directories/folders,files or both
* **ls**(list) 
example: ls
This means that it will show everything **Except** hidden files and hidden folders. 
**ls -a**(list include hidden)
example: ls -a

**ls -la**(Shows hidden items with permissions displayed)
example: ls -la

Which show the following
drwxr-x-r-x
Above us show the permissions for different groups and below is what each letter stands for.

*d: directory which is our folder or well directory
*r: stands for read
*w: stands for write
*x: stands for execute

The first d**rwx** is the users area, the second group **r-x** is for groups, and the third last section **r-x** is for the guest who don't have an account to the computer.

# GIT Commands

Similar to Visual Studio Code(VS Code) instead of using the easy method like pressing the initialize and + symbol to stage a modified file, we use the terminal to basically do the same thing.

**git init**

This Command initializes a local git repository(database)

**git status**

Verifies your files in the working directory to see if it's tracked or not.

**git add .**

this command stages all of your files from untracked to tracked.

**git status** 

Checks if the stages and commits are tracked

**git commit -m**

Pushed the tracked files with a message

example: git commit -m "add header"

