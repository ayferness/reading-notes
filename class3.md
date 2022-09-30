#  Revisions and the Cloud
Links to an external site.Git
Git is a distributed version control system (DVCS) that stores data in a file system made of snapshots. Saving your project is called a commit, which creates a snapshot of the file.

Every change made to a file is tracked by Git, which allows it to detect file corruption or loss of data.

Files in Git exist is three main states:

Committed: data is securely stored in a local database
Modified: filehas been changed but not committed to the database
Staged: prepares a file to be committed
Links to an external site.GITFLOW:ACP
To save changes to GitHub from your computer to the cloud, input the following commands to your terminal:



Revisions and the Cloud .
Today we learned about Git and GitHub. I learned they are two different things. The major difference is that GitHub is mainly for code storage and whereas for Git is a version control system that allows you to revisit various versions of a file or set by recording changes. You can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. Therefore, by utilizing a version control system, mistakes with files can easily be rectified.

See more information hereLinks to an external site.

Git terminal commands include:

* git clone = clones the repository (these are really just a folder)
* git add . = adds all the files changed that are to be tracked by Git
* git commit = -m ‘message here’ - Commit changes
* git commit push origin main = Sends changes to GitHub
* git status = Lets you know the standing of modified files and whether they are staged to be committed or not, or if there are commits needing to be pushed
* git stash = Allows you to temporarily hide changes that your not ready to commit
