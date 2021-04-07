# **Software Enginnering Sessional**
**ECE-3118**

## **Some git commands:**

## git init: 

We use this command for version controlling.

```
$ git init
```

## git add:

We use this  command for updates the current content of the working tree to the staging area. To stagged all the unstaged file we use:
```
$ git add -A
```
And for stagging spacific file, We use: 
```
$ git add <file name>
```
## git status: 

The git status command is used to display the state of the repository and staging area. It allows us to see the tracked, untracked files and changes.

```
$ git status
```

## Git Commit: 
It is used to record the changes in the repository. It is the next command after the git add. Every commit contains the index data and the commit message. Every commit forms a parent-child relationship. When we add a file in Git, it will take place in the staging area. A commit command is used to fetch updates from the staging area to the repository.

``` 
$ git commit -m "<Commit message>"
```

## Git Clone: 
The git clone is a command-line utility which is used to make a local copy of a remote repository. It accesses the repository through a remote URL. Usually, the original repository is located on a remote server, often from a Git service like GitHub. The remote repository URL is referred to the origin.
```
$ git clone <repository URL>
```

