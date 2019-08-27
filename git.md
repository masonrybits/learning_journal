# Git

**Git** is a version control system that allows users to store and access data in a file system made up of snapshots. Git keeps track of every singe change applied to ant file and directory. Therefore, one can access and make revisions to previous snapshots. Git also foster collaboration process by allowing team members to have more knowledge of each other’s activities with certain files, and granting administrators more control over revision privileges.

Files in Git can reside in three main **states** :
* Committed Data: is securely stored in a local database
* Modified: File has been changed but not committed to the database 
* Staged Flagged: a file’s changed version to be committed in the next snapshot

Below are a few helpful commands for git.

Command | Action
--------| -------
`git clone repository’s URL`| create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL
`git status`| determine the state of files
`git add filename` | track one file only by using the following format
`git commit -m “comments”` |  commit the changes and comment on why the changes are committed
`git push origin master`    | pushe changes from the local “master” branch to the remote repository named “origin”
`git pull` | fetch and merge remote changes in your working directory