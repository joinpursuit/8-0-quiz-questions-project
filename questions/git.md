## Git Questions....

<p>&nbsp;</p>

## Q. What is a Git Repository?
>**Answer:** A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your project, building a history over time. Meaning, if you delete the .git/ folder, then you delete your project’s history.

<p>&nbsp;</p>

## Q 2. how do you create(Initialize) a Git Repository?
>**Answer:** ----->    $ git init
- This creates a new subdirectory named .git that contains all of your necessary repository files — a Git repository skeleton. At this point, nothing in your project is tracked yet. See Git Internals for more information about exactly what files are contained in the .git directory you just created.

<p>&nbsp;</p>

## Q 3. What is a Git commit?
>**Answer:** Git commit creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times. You should make new commits often, based around logical units of change.

- If you want to start version-controlling existing files (as opposed to an empty directory), you should probably begin tracking those files and do an initial commit. You can accomplish that with a few git add commands that specify the files you want to track, followed by a git commit:

- $ git add *.md
- $ git add *.js 
- $ git commit -m 'Initial project version'
(never forget to close your quotation marks)