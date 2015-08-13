---
title: Git Dictionary 
tags: featured
layout: post
date: 2015-08-12
---
## What is Git?

![optional image text]({{site.baseurl}}/assets/images/screenshot1.jpg)



[Git is a version control application](https://mac.github.com/) that allows multiple people to work on and make edits to the same project. If there is a conflict of changes, Git will save two copies and you can later merge changes together without losing any work. You can also revert to an earlier version because Git keeps a snapshot of every change ever made to each file. Git thinks about data as a stream of snapshots rather than a set of files and the changes made to each file over time.

There are three main sections of a git project: the Git directory, the working directory, and the staging area.

The Git directory is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

The working directory is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit. It’s sometimes referred to as the “index”, but it’s also common to refer to it as the staging area.

**The** basic Git _workflow_ goes something like this:

1. You modify files in your working directory.
2. You stage the files, adding snapshots of them to your staging area.
3. You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.

Git operates locally. For instance, to browse commit history (using git log), git doesn’t need to go to the server to obtain the history because the entire history of the project is on your local disk. This makes most operations almost instantaneous.

Git generally only adds data: meaning it’s hard to erase things in Git. You CAN lose or mess up changes you haven’t committed yet, but after you commit a snapshot to Git, it’s very difficult to lose.

Github allows you to browse and study other user’s projects by “forking” or copying other repositories. You can even suggest changes to other repositories by sending a pull request. By doing this, Git wants users to learn from each other and help each other in the spirit of open source development.