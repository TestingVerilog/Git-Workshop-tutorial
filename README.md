# Git-Workshop
It's a workshop about Git!

A reminder of some helpful commands:

Shell:
cd to move around a directory
mkdir takes an argument <name> and creates a dir with that name
dir lists info about that directory

Repository setup:
git init starts tracking with git in the folder you are in
git clone <url> will clone the repo with the url you provide (can be done via http or ssh)

Git:
git add takes n number of args as file names or blob syntax paths to stage these files for your commit 
git commit creates the commit with your staged changes. If the -m "" flag anddtext field are not provided in that line, the commit command you will prompt you for a commit message in your defualt text editor 
git push will send your updated history to an upstream remote repository hosted on a git server. This is github for the sake of this demo

Branching and Merging:
git switch <branch-name> or git checkout <branch-name> will move to a different branch of your git tracked project
git merge <branch-name> or git rebase <branch-name will merge or rebase the chosen branch with the branch you are currently on. merge and rebase are similar but nuanced