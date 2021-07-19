
# Git it!

**Q:** Where do you access git and how is it installed?
> Using iterm (or any terminal), you first must install Homebrew. <br>(/bin/bash -c "$(curl -fsSL
 https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)") <br>
> Homebrew allows you to directly install varuious programs from a terminal.  In your terminal, a user can download git.  Git allows you to create a repository thats works cohesively with GitHub. <br>
> Common git commands are:<br>
`git add`  Stage a change executed in the repository> <br>
`git commit` Recording a change executed in the repository <br>
`git push` Update remote repository with the newly committed changes
---
**Q:**  What is a branch in Git and why is it beneficial? How is a branch created and accessed via the terminal?

> A branch is an isolated enviroment to test new new/different code without affecting the master branch
If satisfied with the new code, the user can them commit the changes and merge the changes to the master branch.
Branches allows multiple members to work on different parts of the project at the same time without afftecting the main branch. With this in place, this allows visibility as to which team members made their respective changes to a project. <br>To create a branch, execute the following code in the command line. <br>
>`git branch <branchname>` <br>
>To work within the branch, either of the following lines within the command line <br>
`git checkout <brandhname> ` <br>
Or <br>
`git checkout -b <branchname>`

---

**Q:** What are the different ways that you can undo a commit?

> To review the code at an earlier stage enter the following in the terminal <br>
`git checkout <commit id> `<br>
 To record some new commits to reverse the effect of some earlier commits <br>
`git revert <commit id>` <br>
To delete past commits and revert the code to a past commit, add the following line to the terminal <br>
`git reset <commit id> --hard`

