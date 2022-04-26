# Chapter: Introduction to Git
## What is Git:
- It is a version control system
- It keeps a historical record of each save.
- Git works on a local machine.
- Git thinks about its data more like a stream of snapshots

### Goals of Git (inception in 2005):
1. Speed
2. Simple Design 
3. Strong support for non-linear development (thousands of parallel branches)
4. Fully Distributed
5. Able to handle large projects

### Stages in Git:
1. Modified - Changed the file but have not committed it to your database.
2. Staged - have marked a modified file in the current version to go into your next commit snapshot.
3. Committed - The data is safely stored in your local database.

### Git Daily task:
- Create thing
- Save thing
- Edit thing
- Save the thing again (**Imp**)

## What is Version Control
- It is a system that records changes to a file or set of files over time so that you can recall a specific version later.
- It helps provide clarity as to when & why you did it and what the content of the change was and is open for review at any time in the future.

### Types of Version Control Systems:
1. Local Version Control System: e.g.- RCS
2. Centralized Version Control System: e.g.- Subversion, Perforce
3. Distributed Version Control System: e.g.- Git, mercurial, Bazaar

---

# Git Basics
## Basic Git Workflow:
- These are common Git commands used to manage projects and upload your work onto GitHub.

* Create GitHub Repo with README.md file.
* To Copy this repository onto your local machine 
    - Click the green "Code" button.
    - Select SSH Option & copy the line below it.

* To clone: write command in the terminal ` git clone ` followed by URL copied in previous step.
    - Example ` git clone git@github.com:USER-NAME\REPOSITORY-NAME.git `

## Using Git Work Flow:
1. Create a new file using the command `touch hello_world.txt`.
2. Type `git status` in the terminal.
    - hello_world.txt file is shown in red color which means that this file is not staged.
3. Type `git add hello_world.txt`.
    - This add your hello_world.txt file to the staging area in Git.
4. Again type `git status`
    - now file is shown in green which means that file is now in staging area.
5. Type `git commit -m "Add hello_world.txt"`.
6. Again type `git status`.
    - Output would be "nothing to commit, working tree clean", indicating your changes have been committed.
7. Type `git log` to look at outputs.

## Pushing Work to GitHub
- Type `git push origin main` to push your work to github.
- Type `git status` and you shouls get output "Your branch is up to date with 'origin/main' nothing to commit, working tree clean".
---
**Notes:**
1. "Your branch is ahead of 'origin/main' by 1 commit" just means that you now have newer snapshots than what is your remote repository. 
2. Press `q` to escape if the terminal is stuck in the screen with (END) at the bottom.
3. Basic Git Syntex:` program | action | destination`