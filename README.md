# Git, Github and Readme Format

### Table of contents
* [Introduction](#introduction) 
* [Technologies](#technologies)
* [Commands](#commands)
* [Syntax](#syntax)
* [Source](#source)
* [Examples](#examples)


### Introduction
This project was made as result of a practice of Git and Github commands.
And also learn about the content of a Readme.md file.

README.md. file in a project must be include the following elements:
* Titles and internal titles
* Introduction - the project's aim
* Technologies
* Launch

Consider also using additional elements such as: 
* Table of contents
* Illustrations
* Scope of functionalities 
* Examples of use
* Project status 
* Sources
* Other information

### Technologies
* HTML
* CSS
* Git
* GitHub

### Commands
| Function name | Description                    |
| ------------- | ------------------------------ |
| `git clone url`      | This command saves the directory as the default directory name of the git repository       |
| `git checkout branch_name`   |  Reach to the target branch    | 
| `git merge new_branch`   | Merge the branch to target branch    | 
| `git commit --amend`   |  When there is a situation when you forget to add some files to commit and want to undo any commit     | 
| `git branch`   |  List all of the branches in your repository     | 
| `git branch branch_name`   |  Create a new branch    | 
| `git branch -d branch_name`   |  Delete the specific branch     | 



### Syntax
Set your username:
```
git config --global user.name "FIRST_NAME LAST_NAME"
```
Set your email address:
```
git config --global user.email "MY_NAME@example.com"
```

#### Push files to your Git repository
* Step 1: Go to Github repository and in code section copy the URL.
* Step 2: In the Command prompt, add the URL for your repository where your local repository will be pushed.
```
git remote add origin repository_URL
```
* Step 3: Push the changes in your local repository to GitHub.
```
git push origin master
```
Now in the GitHub repository, the pushed files can be seen.



### Source:
How to Write a Good Readme                   
https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project                   
                   
MarkUp Language Tutorial                   
https://commonmark.org/help/tutorial/                   
                   
Example                   
https://github.com/kriasoft/Folder-Structure-Conventions/blob/master/README.md 


