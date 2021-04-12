# Git

## What is Git :
1. Snapshots
* Git is a DVCS that stores data in a file system made up of snapshots.
  * DVCS : A Distributed Version Control systems (DVCS)
2. Local Operations
* Git mostly relies on local operations because most necessary information can be found in local resources.
3. Tracking Changes
* Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will 
* always detect file corruption or loss of information in transit.
4. Loss of Data
* Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. 
  Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
5. States
* Files in Git can reside in three main states:
> Committed
> 
> Modified
>
> Staged


![States](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Download Git

Git can be installed in three ways:
1. Install as a package
2. Install via another installer
3. Download and compile the source code.

## Initial Customization
#### After making sure Git has been installed, there is some steps wich completed once on any machine :
* Git tool called **git** config allows the setting of configuration
* Type the following into Terminal or Command Line:
 
 **git config --global user.name "Username"**
 
 **git config --global user.email "example@email.com"**
 
 ***you can use the default text editor or change it with this command line:**
 - $ git config --global core.editor emacs **for the emacs text editor**
 
 ## Getting Help
 **There are three ways to get more information with these particular command :**
 > git help command
 > 
 > git command --help
 >
 > man git-command
 
 ## Setting up a Git Repository
 
Importing | Cloning
------------ | -------------
To import an existing project or directory into Git | copy of an existing Git repository from a particular server

## Workflow

![Workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## The Life Cycle of File Status

![Life Cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

> Check File Status **$ git status**
> 
> Tracking and Staging a New File 1. Single File - **git add filename** 2. All Files - $ git add *
> 
> Committing a File **$ git commit -m “made change x,y,z”**
> 
> Committing All Changes **$ git commit -a**
> 
> Pushing Changes **$ git push origin master**
> 
>


 
 



