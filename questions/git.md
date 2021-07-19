# Git

**Q:** What is Git and why is it used by software developers?

> **A:** Git is known as a version control tool (VCS). It's an open-sourced software that enables you to back up and merge your code in a productive way. It's basically controlling what version we've got and provides an automatic way to track changes in software projects, giving creators the ability to view prior versions of files and directories, develop speculative features without disrupting the primary codebase, securely backing up the project and its history, and collaborate easily and conveniently with others. It has the ability to rewind. With Git, you have the power to say I want everything that we've done except the changes made last week. It's like splicing out changes made in the middle. You can also switch back and forth between two versions - one with a special feature and other without it. It's similar to REPL but it's more powerful and manual. Plus, you've got the ability for people to work together on projects. 

---
---

**Q:** How do you use Git and what are some of its commands ?

> **A:** We use Git via the command line program called git, which lets us transform an ordinary folder into repository (or repo for short) that enables us to track changes to our project. 
- To see if the git executable is present type `which git` into the command line and you should see a it's file path `/usr/local/bin/git`
- To initialize a repo, use `git init` on the command line
- To check which files are staged and unstaged `git status`
- To stage a file, use `git add`
- To create a new entry in the git repo's history, use `git commit -m "message"`
- To view what changes have been made between tracked and untracked files, use `git diff` 
- To see the latest commits, check `git log`

Note that the order of commands here is important.

---
---

**Q:** How do you make sure you don't mistakenly git your home directory and what's the rule for naming files/folders?

> **A:** It's not recommended to git repo your home folder. You can use the `ls -a` on the command line to see all the hidden files and if you're in a git repo, you will find the following git files `. .. .git`. If we remove the .git repo, then it's no longer a git repo. How you name your files/directories is important because having a space in your name, for example, could be interpreted by the command line as a new file/directory. So it is recommended to use kabob casing or snake casing. 

---
---