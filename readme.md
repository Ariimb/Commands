
# Comand line

Commands are directives to the computer program to perform tasks.

#Create and delete directories

Mkdir "Directory name": Allows users to create or make new directories.
If directories within a named path do not exist, an error will be generated. 
To have CMShell automatically create non-existent directories in a path, be sure to include the -p or --parents option.

Example usage: Example creation of a single directory using mkdir with the verbose -v option. [writingteam /]$ mkdir -v films mkdir: created directory `films'
 
Example creation of nested directory structure. The -p option will create any folders that don't already exist. This example combines mkdir with the -p option.
[writingteam /]$ mkdir -p /tv/shows/

The “<OPTION>” variable displayed in the above example can be populated with any of the following options:

Option Description -p, --parents If parent directories in the specified path do not exist, automatically generate them to accommodate (and do not generate an error). 

-v, --verbose Display the operation’s execution step by step. 

-h, --help Display help information for this command.

rmdir "direction name": Removes the directory from the system. This can help clean up space on your computer and keep files and folders organized. 
Common options: -p.

mv: Move or remove directory. Without this command, you would have to individually rename each filw which is tedious.
Common options: -i, -b.

pwd: Its used to print the current directory you’re in. 
As an example, if you have multiple terminals going and you need to remember the exact directory you’re working within, then pwd will tell you.

Example: pwd [option(s)]

echo: prints text to the terminal window and is typically used in shell scripts and batch files to output status text to the screen or a computer file.
common options: -e, -n

Example: echo [option(s)] [string(s)]

#Navigate

Cd "Repository name": To navigate in your repository.

The cd command, also known as chdir (change directory), is a command-line shell command used to change the current working directory in various operating systems. 
It can be used in shell scripts and batch files.

usage: If the user's current working directory is the home directory (~), then entering the command ls followed by cd games might produce the following transcript:

user@wikipedia:~$ ls workreports games encyclopedia text.txt user@wikipedia:~$ cd games user@wikipedia:~/games$

The user is now in the "games directory".

Cd Options: 

cd by itself or cd ~ will always put the user in their home directory.

cd . will leave the user in the same directory they are currently in (i.e. the current directory won't change). 

cd ~username will put the user in the username's home directory.

cd dir (without a /) will put the user in a subdirectory

cd .. will move the user up one directory.

cd - will switch the user to the previous directory.

Ls: Check the contents of your directory.

#Compare

Cmp: To compare two files. It tracks the differences between the changes made on a file.

#Find files, folders and inside files.

Find (route) "file name": To find a folder and file, it allows you to view existed files.

#Create and edit text files.

Nano "name of file": To create and edit text files.

cat: Read a file, create a file, and concatenate files. 
Is one of the more versatile commands and serves three main functions: displaying them, combining copies of them, and creating new ones. 
Common options: -n

Example: cat [option(s)] [file_name(s)] [-] [file_name(s)]

#Get the state of the computer.

lscpu: Check the state of the computer.

# Git Commands

Commands used in git with their function and example.

#Initial configuration

Git config --global user.name "Your name": To configurate your name.
Example: git config --global user.name "Ari Martinez"

Git config --global user.email "Your email": To configurate your email.
Example: git config --global user.email "ammb01@live.com.mx"

#Start a project from zero or cloning an existin repository

Git init "name of the project": Create a new repository.

The init command stands for initialize. 
Once you run "git init", Git will initiaize a hidden directory called ".git" in the projects root directory.

Git clone: Clone a project from a remote repository.

#Basic workflow commands to stage and commit.

git init: Command to initialize a new git repository or reinitialize an existing one.

git status: The git status command is used to display the state of the repository and staging area.
It allows us to see the tracked, untracked files and changes. 
This command will not show any commit records or information.
Example: Himanshu@himanshu-PC MINGW64 ~/desktop/NewDirectory (master)
$ git status
On branch master
nothing to commit, working tree clean

git add "name of file": Adds new or changed files in your working directory to the Git staging area.

git commit: It saves all staged changes.

Important git commit options: -m <message> Sets the commit´s message.
-a includes all currently changed files in this commit.
--amend Rewrites the very last commit.

Example: git commit -m: "change titles and styling on homepage"
git commit -a -m "change titles and stylig on homepage"
git commit --amend -m "New commit message"

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


