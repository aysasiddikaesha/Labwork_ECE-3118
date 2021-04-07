# **Software Enginnering Sessional**
**ECE-3118**

## **Some git commands:**

## Git Init: 

We use this command for version controlling.

```
$ git init
```

## Git Add:

We use this  command for updates the current content of the working tree to the staging area. To stagged all the unstaged file we use:
```
$ git add -A
```
And for stagging spacific file, We use: 
```
$ git add <file name>
```
## Git Status: 

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

## Git Head: 
The HEAD points out the last commit in the current checkout branch. It is like a pointer to any reference. The HEAD can be understood as the "current branch." When we switch branches with 'checkout,' the HEAD is transferred to the new branch.
```
$ git show HEAD
```
## Git Remote:
To check the configuration of the remote server, run the git remote command. The git remote command allows accessing the connection between remote and local. If you want to see the original existence of your cloned repository, use the git remote command. It can be used as:
```
$ git remote 
```

Git remote supports a specific option -v to show the URLs that Git has stored as a short name. These short names are used during the reading and write operation. It is used as:
```
$ git remote -v 
```
When we fetch a repository implicitly, git adds a remote for the repository. Also, we can explicitly add a remote for a repository. We can add a remote as a shot nickname or short name. To add remote as a short name, follow the below command:
```
$ git remote add <short name><remote URL>  
```
To fetch the data from your remote projects, run the below command:
```
$ git fetch <remote>  
```
To clone the remote repository from your remote projects, run the below command:
```
$ git clone<remote>  
``` 
When we clone a repository, the remote repository is added by a default name "origin." So, mostly, the command is used as git fetch origin.

The git fetch origin fetches the updates that have been made to the remote server since you cloned it. The git fetch command only downloads the data to the local repository.
To pull the repository, run the below command:
```
$ git pull <remote> 
```  

To share our project, you have to push it upstream. The git push command is used to share a project or send updates to the remote server. It is used as:
```
$ git push <remote><branch>  
```
To update the main branch of the project, use the below command:
```
$ git push origin master  
```
It is a special command-line utility that specifies the .

We can remove a remote connection from a repository. To remove a connection, perform the git remote command with remove or rm option. It can be done as:
```
$ git remote rm <destination>  
```
## Git Checkout:

 The git checkout command is used to switch between branches in a repository. Be careful with your staged files and commits when switching between branches.
 ```
$ git checkout <branchname> 
 ```
## Git Fetch:
We can fetch the complete repository with the help of fetch command from a repository URL like a pull command does.
```
$ git fetch <repository Url>
```
## Git Pull:
We can pull the repository by using the git pull command. The syntax is given below:
```
$ git pull origin master  
```
## Git Push:
Git push origin master is a special command-line utility that specifies the remote branch and directory. When we have multiple branches and directory, then this command assists us in determining our main branch and repository.
```
$ git push origin master  
```