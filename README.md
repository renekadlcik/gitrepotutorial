# First Git tutorial
Mainly aimed for students of the University of Ostrava, course Software engineering.

## Description
This repository lets you try out your first pull request.  

## Table of Contents
- [Students](#students)
  - [2024/25](#year-202425)
  - [Template](#template)
- [Instructions](#instructions)
- [Credits](#credits)

## Students

### <a name="year-202425"></a>2024/25
| Personal number | Done |
|:----------:|:----------:|
|  |  |

### Template
| Personal number | Done |
|:----------:|:----------:|
| R12345 | &check; |
| R54321 | &cross; |

## Instructions
Step-by-step instructions on how to create your first pull request.
1. Fork this project to your account.
2. Clone your forked repository to your local machine.
```bash
$ git clone https://github.com/YOUR_USERNAME/gitrepotutorial.git
```
3. Navigate inside that repository and create a new branch with a name that describes its purpose.  
*(you can add your surname or personal number)*
```bash
$ cd gitrepotutorial
$ git checkout -b BRANCH_NAME
```
4. In the cloned repository, navigate to the sub-folder :file_folder:**students/YEAR/** and create a new **.md** file with your personal number as the filename.  
*(e.g. 'R12345.md')*
5. Write your name inside this file.  
*(e.g. 'John Doe')*
6. Now that we've modified the staging area, we need to stage the changes and commit them.
```bash
$ git add .
$ git commit -m "MESSAGE"
```
7. So far your work is only local and you need to push the changes to your remote repository.
```bash
$ git push -u origin BRANCH_NAME
```
8. Last thing to do is to create a pull request. Head to your remote repository on GitHub (or original repository) and you should be able to see a button called "Compare & pull request".
Click it and you'll see a pull request page. You can select the branch from where I want to merge changes and also where to.
9. And you're all done, wait for a reviewer to review your changes and merge it to the main branch. Once it's done, you should see a checkmark by your personal number.

## Credits
This tutorial project was created by Radim Pesa.  
Inspired by https://trygit.js.org/.