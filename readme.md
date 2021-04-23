
# Comand line

Commands are directives to the computer program to perform tasks.

#Create and delete directories

Mkdir "Directory name": Allows users to create or make new directories.

rmdir "Directory name": Removes the directory from the system.

#Navigate

Cd "Repository name": To navigate in your repository.

Ls: Check the contents of your directory.

#Compare

Cmp: To compare two files.

#Find files, folders and inside files.

Find (route) "file name": To find a folder and file.

#Create and edit text files.

Nano "name of file": To create and edit text files.

#Get the state of the computer.

lscpu: Check the state of the computer.

# Git Commands

#Initial configuration

Git config --global user.name "Your name": To configurate your name.

Git config --global user.email "Your email": To configurate your email.

#Start a project from zero or cloning an existin repository

Git init "name of the project": Create a new repository.

The init command stands for initialize. 
Once you run "git init", Git will initiaize a hidden directory called ".git" in the projects root directory.
Git clone: Clone a project from a remote repository.

#Basic workflow commands to stage and commit.

git init: Command to initialize a new git repository or reinitialize an existing one.

git add "name of file": Adds new or changed files in your working directory to the Git staging area.

git commit: It saves all staged changes.

git log: Review and read a history of everything that happens to a repository.

#Push to a remote repository.

git push -u "direction": Used to upload a local repository content to a remote repository.

git remote: Used to manage your central servers for hosting your git repositories. 

After run the command "git init" you will run the command "git status".
git status: See the status of the files. 

#Branches.

You can consider branches in Git as paths. Here are the different commands to check the branches.

git checkout: It switches between branches in a repository. 

git merge: Integrate changes from another branch.

git branch: Create, list, rename, and delete branches.

git branch -d: Remove merged branch.

git config: Set git configuration values on a global or local project level.

#Gitflow.

git flow init: Initialize from a git repository.

git add.: Add files in a folder.

git flow hotfix (start/finish): Start or finish a new hotfix branch for hotfix branches.

git flow support: To list a support branch. 


