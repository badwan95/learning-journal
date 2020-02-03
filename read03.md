# Revisions and the cloud

## Git 

**Git** is a way to share code between multiple people, its a version control system, you can code on your own computer and then upload it to the cloud.

We can use both git and github for a big team to work together on the same file without messing each other's work.

First you have to download git from http://git-scm.com/ , then customize it using:
> git config 
and then set a user name by doing the following code:
> git config --global user.name "your name"

> git config --global user.email "your@email.com"

To check settings, use
> git config --list command.

Snapshots are commits that are basically "save as" in other programs, every commit has an ID and a label (a message to define what you changed), git keeps history of what those snapshots look like.

The "HEAD" means the most recent commit, and its a special git label.

**You must follow the A-C-P way; add, commit and push.**

* Typical commands in git terminal:

> git remote -v
to get the url of the repository

> git clone URL

After cloning, you would have downloaded the repository locally.

> code .

> git status

> git add filename

> git commit -m "your message"

> git push origin master
