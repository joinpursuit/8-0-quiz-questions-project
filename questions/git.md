# Git

**Q-1:** How is `Git` a version control system?

> A-1: No, Git is different than your terminal. While Git can be ran using the terminal, it is not the same thing. Git is a `version control system` that tracks your project, that can be visualized as a lengthy board game that takes hours and hours, creating "save" points. If you were to take a photo of the game board and pieces, that would be your version control system of a "save" point of the game, at that point in time. Then, if a minute later after you get up, your pet jumps on the table and messes everything up scattering the game onto the floor, you have a place to come back to (your photo) that "saved" your progress, where you can re-set all the pieces to where they were before they went all over the floor. The way `Git` works is that you have a project you're working on, and you may want to test different versions of your code. The code you have now is working, but what if you wanted to delete the code taking up half your file and re-write the code? And then, if that re-written code didn't work and you wanted to go back to what you originally had? You would want to have a "saved" version of that original code file. That is what Git does. It saves your progress at a particular point in time, when you tell Git to "save" it. You can then see all your previous versions of your code, from when you first began your project to where it currently is.

---

**Q-2:** Is `Git` the same thing as your terminal? 

> A-2: No, you have to install `Git`. Then you run it on your CLI, such as Terminal, iTerm, the VS Code terminal, etc. You will want to know a variety of **shell commands** to easily navigate between directories and files on your computer. `command + shift + .` toggles hidden files on/off. A few shell commands that are helpful:

* `cd` - change directory
* `mkdir` - make directory
* `touch` - create a file
* `ls - a` - lists the files (all, including hidden ones)
* `rm` - remove a file (be careful!)
* `rmdir` - remove a directory (be careful!)



---

**Q-3:** What are a few useful `git` commands?

> A-3: For Git, you will want to know a few useful git commands:

* `git clone <url to repository>`
* `git add <individual file name, or> `.` <for all files>` 
* `git commit` - if you want to enter the commit message in your default code editor
* `git commit -m` - if you want to enter commit message using command line, but use quotes
* `git push`
* `git log` - lists the commits you've made, type `:q` to quit

Examples:
```
git clone project.git
git add git.md
git commit
git commit -m "commit message"
git push
git log
```
---
