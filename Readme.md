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

If we have more than one branch inside our repository we can move between them. Use next command: 

```sh
git checkout "branch_name"
```

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

## Merge and delete in Git

When we wnat add info from one branch in the second we can merge it. For this Git have next command:
```sh
git merge "branch_name"
```
WARNING!!!
Last command will added info from branch "branch_name" in branch where you are. 
After succesful merging we can delete branch, for it you can use next command:
```sh
git branch -d "branch_name"
```
But if you want delete branch without any question from Terminal you can use next command:
```sh
git branch -D "branch_name"
```
And sometimes we can make conflict when we are merging branches. It happens because we have in the similar positions in both branches some changes. And when we use command merge Git can't done this conflict and will ask you to do that. After done conflict commit your changes.