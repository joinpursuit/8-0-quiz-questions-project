# Git

**Q1:** What is the significance of the -m flag of the git commit command? What would happen if it was left out?

> The -m flag is essential to git commit because without it the command would not work. It provides each commit, containing each previously added file, with a label that (hopefully) describes it and is appropriate. Without a label, you'd have to go through a lengthier process to know about each commit's contents. 

---

**Q2:** Consider a situation where you've accidentally messed with your code, it no longer works how it should, undo isn't working out as you need it to, and you need to find your last checkpoint. What would be your process using git?

> You would first need to use `git log` to view all of your most recents commits. This shows each (hopefully) descriptive commit message and its accompanying sha string. By entering `git revert sha` where sha is the long character string, into the repository's main directory you can get rid of your current code and replace it with what the file once had.

---
**Q3:** Within Git are four states that files can be in, and commands that can move files upwards from the four states. Name the states and the commands used to move between each.

> UNSTAGED -> `git add` -> STAGED -> `git commit` -> LOCAL REPOSITORY -> `git push` -> REMOTE REPOSITORY

> These are the commands used to move upward and onto an online repository, which is typically GitHub. Files can move backwards from there with `git pull` and within the stages with `git revert`.
---
