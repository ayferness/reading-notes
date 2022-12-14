#  Revisions and the Cloud

Git is a distributed version control system (DVCS) that stores data in a file system made of snapshots. Saving your project is called a commit, which creates a snapshot of the file.

Every change made to a file is tracked by Git, which allows it to detect file corruption or loss of data.

Files in Git exist is three main states:

**Committed**: data is securely stored in a local database

**Modified**: filehas been changed but not committed to the database

**Staged**: prepares a file to be committed

**What is ACP ( Add+ Commit+ Push)**
For Saving changes to GitHub from your computer to the cloud, input the following commands to your terminal:
1- git add (name of file)
2- git commit -m “write commit message”
3- git push origin main


Revisions and the Cloud .
Git and Github is different.GitHub is mainly for code storage and whereas for Git is a version control system that allows you to revisit various versions of a file or set by recording changes. You can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. Therefore, by utilizing a version control system, mistakes with files can easily be rectified.


Git terminal commands include:

* git clone = clones the repository (these are really just a folder)
* git add . = adds all the files changed that are to be tracked by Git
* git commit = -m ‘message here’ - Commit changes
* git commit push origin main = Sends changes to GitHub
* git status = Lets you know the standing of modified files and whether they are staged to be committed or not, or if there are commits needing to be pushed
* git stash = Allows you to temporarily hide changes that your not ready to commit
