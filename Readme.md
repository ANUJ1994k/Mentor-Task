#Git and GitHub
> #Git:

Free and Open Source version control system.

Git- Git is a tool to track changes on code over time. #GitHUb: -Github is a website where you host your repository online.

#Command line Interface

Directory-> Folder Terminal or Command Line -> interface for text Commands CLI-> Command Line Interface cd- Change Directory Code Editor:- Word Processor for Writing Code Repository:-Project or the folder/place where your

Clone: Bring a repository that is hosted somewhere like Github into a folder on your local machine.

add :-> track your files and changes in Git. commit:- Save your files in Git. push-> Upload Git commits to remote repo like Github,gitlab, gitbucket. pull:- Download changes from remote repo to your local machine , the opposite of push.

Connecting to GitHUb with SSH:
You can connect to GitHub using the Secure Shell Protocol (SSH) Which provides a secure channel over an unsecured network.

GitHub Workflow Local Git Workflow
Write code 1. write code

Commit Changes 2. stage Changes (Git add)

Make a pull Request 3. Commit Changes (git commit)

                            Push Changes (Git Push)
 		                  Make a Pull Request 
If you're not on the main branch, switch to it using the git checkout command: git checkout main

Create a New Branch

To create a new branch, you can use the git branch command followed by the branch name you want to create:git branch new-feature

This command creates a new branch named "new-feature" but doesn't switch to it yet.

Stage Changes Use the git add command to stage the changes you want to commit. For example, to stage all changes, git add .
