# Overview

### What is git
Git is a distributed versioning control system. Which essencally means it is a program that does not require a central server, and allows you to manage your code in a way that allows you to role back changes, Merge if two people end up changing the same file, and in genral colaberate much better.

### Differences between git and svn
The biggest difference is that with git, Every repo is self contained, If you have cloned a repo, You localy have all version history, And others can clone directly from you. Where as svn requires that you be connected to the central server. This means if you do not have internet connection with git you can still commit, roleback and so on. Also it means if your git server crashes, You have a full backup on every developers desktop.

That said if you are use to an svn enviroment, you will have to get use to the fact that git commit DOES NOT send it to the remote server, and if you forget to git push, your code is only on your desktop.

Here are a few quick commands that will end up being 90% of what you use
Command | Description
----|----
git clone [Repo] | Initially downloads a given repo
git commit -m "txt" | Commits changes to your local repo
git pull | Pulls the changes from the default remote ( Usually github )
git push | Pulls changes from the default remote
git add --all | Adds all unversioned files to git
git add some/file | Adds a specific File to git
git mergetool -t meld | How to merge if muliple files are overwitten ( requires meld to be installed as well )





