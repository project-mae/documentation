# Git Cheatsheet
Here are some commands that are useful to know for contributing to Project MAE.

## Before You Make a Change
Before you make a change, you should make sure you have the most up to date
version of the repository.

To see what branch you are on:
```
git branch
```

To switch to the main branch:
```
git checkout main
```
If you would like to switch to a branch other than the main branch, replace 
`main` with the name of the branch you want to use.

To download and pull the latest version of the branch you are using:
```
git pull
```
If the repository is private, you may be asked to enter credentials.

## To Make a New Branch for a Pull Request
If the change you are going to make needs to be sent using a pull request, you
can create a branch that is based on your current branch using the following
command:
```
git branch NAME
git checkout NAME
```
Where `NAME` is the desired name of your new branch for your pull request. Make
sure that this name is unique.

## To Create a Commit
Any changes you submit to the repository are grouped into units called Commits.
Commits are made by marking files that you have changed, also known as staging
them, and then wrapping them together with some extra information, such as a
summary and authorship information.

To see what files have been changed:
```
git status
```

To stage all changes:
```
git stage -A
```

To stage a single file or directory:
```
git stage FILENAME
```
Where `FILENAME` is the name of the file or directory you want to stage. You
can also see what changes have been staged or are not staged from 
`git status`.

To create a commit with your staged changes:
```
git commit -m "MESSAGE"
```
Where `MESSAGE` is a brief summary of your changes.

## Uploading Commits to the Repository
To push your new commits to the repository:
```
git push origin TARGET_BRANCH_NAME
```
Replace `TARGET_BRANCH_NAME` with the name of the branch on the online version
of the repository that you would like to push to. The branches on the online
repository may be different than the local version of the repository that is on
your computer.

## Additional Assistance
If you need assistance with using Git, feel free to contact the Repository and
Release Team for additional information or help with anything related to Git or
GitHub.

