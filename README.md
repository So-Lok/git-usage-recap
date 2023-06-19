## Git and Github

# How to initialise a github repo

To initialise a repo in your local environment, create a directory and use the command:
```
git init
```
This will setup the current directory as a repo

## Basic Git Commands
1. ``` git add <filename or filepath> ``` or  ``` git add . ``` for current directory
2. ``` git commit -m "<message>" ```
3. ``` git push ```
4. ``` git pull ```
5. ``` git clone <branch> ```
6. ``` git status ```
7. ``` git log ```

# Git add
Adds the contents of specified file(s) or directory to the index. The index holds a snapshot of the current tree and the content within will be taken as the contents for the next commit made

You can use ``` git status ``` to get a summary of files which have been added or have yet to be

# Git commit
Records changes added to the index to the repository.

# Git push
Uploads the contents/changes made in the local repository to the online repo on github.

For the first push, you may want to set up the upstream which refers to the main repo that you will be pulling and pushing to.

``` git push -u <remote-name> <local-name> ```
 
