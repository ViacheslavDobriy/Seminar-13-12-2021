# Instruction for Git

## What is Git?

Git is one of realization System Control Versions. It is the most famous realization in the world/
## Prepairing repository

For creating repository we need to run command 

```sh
git init
```
in folder with repository.

## Creating "Saves"
## Creating "commits"

### Git add

For adding changing in commit there is using command 
```sh
git add "file_name"
```
### Creation commits

For creating commit there is needed execute command 
```sh
git commit -m "Message"
```

## Moving between saves

## Log of actions

If we want see all our commits we should use command:
```sh
git log 
```
But sometimes it takes a lot spaces in terminal and we can use a short version of this command and add option *"--oneline"*:
```sh
git log --oneline
```
And if we want see relationship between branches we can use command option *"--graph"*:
```sh
git log --graph
```

## Branches in Git

<<<<<<< HEAD
## Merge and delete in Git
=======
In the beggining our work with Git we have only one branch with name "master". If we want create more branches we need use next command:
```sh
git branch "new_branch_name"
```
For see all branches in your repository you can use:
```sh
git branch
```

## Merge in Git
>>>>>>> command_branch

