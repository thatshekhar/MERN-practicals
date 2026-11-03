# Lab 2: Git: Remotes, Push and Clone

**Name:** Shekhar 
**Roll No:** 2410303457
**Course:** BCS554 - HTML & CSS Development Lab

## Aim
Connect a repository to a remote, push the commits and clone it.

## Files
- `index.html` - the file that was committed in the repository (final version)

## Commands and output
```
# Assignment 2 - Name: shekhar | Roll No: 2410303457

## Task 1
$ git init --bare -b main ../html-remote
Initialized empty Git repository in ~/html-remote/

$ git remote add origin ../html-remote

$ git remote -v
origin	../html-remote (fetch)
origin	../html-remote (push)

## Task 2
(If git status shows 'On branch master', use: git push origin master)

$ git push origin main
To ../html-remote
 * [new branch]      main -> main

## Task 3
$ git clone html-remote html-copy
Cloning into 'html-copy'...
done.

$ git log --oneline
4b73648 Add next meeting heading
f632f8f Add home page
```

## Screenshot
![Terminal output](images/screenshot.png)

> The image is drawn from the captured command output. Replace it with a screenshot of your own terminal.
