# Git
**Q:** Where do you access git and how is it installed?
> Using iterm (or any terminal), you first must install Homebrew. (/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)")
> Homebrew allows you to directly install programs.  Then you download git.  You can use git in the terminal. Git allows you to great a repository for working directly with GitHub. It also allows you to directly work with VS code. to open, create, and _modify_ documents.
> Common commands are git .add
```
git .add
git .commit
git .push
. code
readme.md code
```
---
**Q:** How do you install git with homebrew and check which version you have?
Try installing git with brew using brew install git.
```
$ brew install git
$ git --version
```
---
**Q:** What do we use git for?
> Git is how we interact with github and visualcode.  It's for **managing** your project.  It helps control our versions of our projects.
---  


**Q:** How is git conflict resolved?
> First, what's git conflict? This is when the same line of a file is modified by different branches or the same file been deleted in a branch but modified in another. In this case, a manual approach is considered as git will not be able to predict whose changes be give the last update/version
---  

**Q:** What's the difference between git remote and git clone?
> _git clone_ makes a new repository in a local machine by copying the remote repository's url  whereas _git remote _ establishes a conection configuration entry in _git config_ for a specific repository url
---  


```js
  636  git add git.md
  637  git commit -m "Git's installation, use version" 
  638  git push 
  
```
