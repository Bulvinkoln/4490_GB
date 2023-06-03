# How to work with Git

### I suppose that you have already install git and visual studio code

## Local work

### Beginning of the work
1. at the very beginning you have to create a directory, for example, git_inst
2. Then you open terminal and go to your new directory:
cd git_inst
3. Type git init, so you show git that it is your git project.

### Work with branches
#### In git you can use branches, they are like directories. You can create branch, work in branch, there would be copy of your files, but they don't edit files in main branch.
* *git branch* show you all branches of your project
* *git branch new_name* creates a new branch
* *git checkout new_name* go to this branch with name new_name
* *git checkout -b new_name* unites two previos commands: creates brench with name new_name and goes to it

### add files to git-project
* to add file to your git-project use command *git add file_name* instead of filename you can use . Than all files in your directory will be added.
* to commit changes to project use command *git commit -m "comment - what did you do"*
* to know about your files and their status you can use command *git status* 

#### Of course you need to save file before you add it to project!

## Github
#### I suppose that you have a github-account
1. To make a copy of smb project in your acc, go to this project, find button Fork and push it. You'll get copy of the project in your acc
2. To get project from github to local computer puth the button Code and copy the link
3. Go to your working directory and in terminal print *git clone ...* where ... is your copied link
4. In terminal print cd and the name of the project
5. You can use the project as local project
6. If you or smbd else edit your project on github, you can get these changes with the command *git pull*
7. When you want to send your changes from local project to github, you need to commit it to local project and after that print *git push* and copy your project to github.