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

repo -> repository

clone -> bring a repo down from the internet (remote repository like Github) to your local machine

add -> track your files and changes with Git

commit -> save your changes into Git

push -> push your changes to your remote repo on Github (or another website)

pull -> pull changes down from the remote repo to your local machine

status -> check to see which files are being tracked or need to be commited

init -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase

#About SSH key passphrases
>You can access and write data in repositories on GitHub using SSH (Secure Shell Protocol). When you connect via SSH, you authenticate using a private key file on your local machine.
>Open Gitbash  Type: "ssh-keygen -t ed25519 -C "your_email"   (Created GIthub profile mail)
>Generating public/private ALGORITHM key pair.
>Enter file in which to save the key (/c/Users/YOU/.ssh/id_ALGORITHM):[Press enter]
