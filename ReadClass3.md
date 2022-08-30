**Revisions and the Cloud**

## Local Version Control 
A Local VCS entails one database on your hard disk that stores changes to files.

## Centralized Version Control 
This system is a single server storing all changes and file versions, which can be accessed by various clients.

## Distributed Version Control

It works like  a CVS but with multiple redundancies!

## What is Git?
Its a DVCS that saves every revision made, it also resides on the local disk, it will track changes and since it is backed up  by multiple servers it will be hard to lose data. 

##Windows Git Websit Download links for future reference!

-[Website Download](http://git-scm.com/download/win)

-[Windows Install Download](http://windows.github.com)

## Graphical Clients

It includes GUI tools or Graphical User Interface, but can also utilize 3rd party tools. 

## Cloning on Git!
This command allows you to clone an entire repository!
*$ git clone https://github.com/test*
This command allows you to clone the repository into a another directory!
*$ git clone https://github.com/test mydirectory*
## Local Repository Structure!
Made up of 3 parts! 

-Working Directory: The actual files reside here.

-Index: The area used for staging

-Head: Points to the most recent commit

##Saving Changes
Files can either be Tracked or Untracked 

Tracked files can be modified, unmodified and staged. Since they are part of a snapshot!

Untracked files are in  the last snapshot and cannot be modified in the current staging area!...

Files go from Untracked to Unmodified to Modified to Stages and back to Untracked and the cycle goes over.

##To check a file's Status

>$ git status

##Tracking and Staging a New File 
<sub>Lots OF CODE! </sub>
Single File
>git add filename

All Files 
>$ git add *

After you use the aforementioned commands you should see this!
>$ git status

>On branch master

>Changes to be committed:

  >(use "git reset HEAD ..." to unstage)
  
  >new file: EXAMPLE

Once you see this you can proceed to committing your files!

## Committing a File 

>$git commit -m "made change x,y,z"

## Commiting All Changes 

>$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.

## Pushing Changes

>$ git push origin master
>
*This command pushes changes from the local “master” branch to the remote repository named “origin”.

*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.

## Stashing Changes

>git stash
>
Great for applying changes and not losing them.

>git stash apply
>Great for continuing projects!



















