# GitDemo

A repository for the SwampWeek 2020 Git Workshop.

Git can be installed from [git-scm.com](https://git-scm.com).

## Command Line

If you have Git installed, then you likely have Git Bash on your system which provides an environment for running Git commands as well as standard unix commands. Useful commands to know are:

```
cd <directory>: Enter a directory
ls: List contents of a directory
nano: Open a file for editing
  - Ctrl + O: Save file
  - Ctrl + X: Exit (prompts for save if modified)
```

Additionally, a notable Git command:

```
git status: Displays tracked and changed files
```

## Mission 0

Create a fork of this repository on GitHub (top right) so you have a workspace where you can make edits. Then, create a local repository by cloning your fork with:

```
git clone https://github.com/<username>/GitDemo
```

## Mission 1

The commands below are used to submit changes from your local repository to the
origin. Add in the arguments for the commands and use them to push these changes to your remote repository on GitHub.

```
git add
git commit
git push
```

## Mission 2

When ready, update your local repository with the instructions for Mission 3 by
pulling from the forked repo with the following commands.

```
git remote add upstream https://github.com/WillBAnders/GitDemo
git pull upstream
```

## Mission 3


The following commands are used to create and switch to 
new branches.

```
git branch
git checkout -b new-branch
git checkout existing-branch
```

Using these, add a new file to the repository (whatever 
you would like!) and commit it to your fork.

On GitHub, you should see the option to create a Pull 
Request from your branch back to the original GitDemo 
repository. Follow the steps there and we'll see what 
results!
