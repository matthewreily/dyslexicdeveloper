title: Git Commands for Us Newbs - Part 1
date: 2014-12-26 15:08:43
tags: Git

---
I am a pretty typical Microsoft developer when it comes to source control. I
spent a few years using CVS and Subversion. For the majority of my career however,
I have used Team Foundation Server.

I now find myself using Git more and more frequently. So this post and hopefully
more to follow, will be a place for me to document common tasks and workflows
as performed in Git.

###List of Git Commands
![](../img/12262014/GitCommands.png)

###Creating and Retrieving Git Repositories
There are two commands associated with creating and retrieving Git Repositories

__init__ - You can use the init command to initialize a directory as a Git repository.
This can be either an empty directory or an existing directory with pre-existing
files and folders.

![](../img/12262014/initCommand.png)

__clone__ - Clone is used when you want to make a copy of an existing repository.
This allows you to view other projects or collaborate with other users.

run git clone [url] - where the url parameter is the project you wish to copy.

![](../img/12262014/clonecommand.png)
