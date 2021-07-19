# GitHub


**Q:** How are git and github related? 

> **A:** - With Github, an online service, it's about managing a team and the whole repository, compared to git, where you’re focused on adding and committing changes locally on your machine without ever needing internet connection. Git is open-sourced (all the code is available on GitHub), while GitHub is a commercial enterprise (not open-source) and the web app is owned by Microsoft. Some of it is open source but it’s a commercial product.  

> In GitHub, it's where the main project is housed. It's a backup and a file management system. And unlike git, it's on a remote server or in the cloud. GitHub also works like social media, where you can share your code globally, contribute, provide/receive comments and get/create pull requests, if anyone wants to make a change in the main repo. 

---
---

**Q:** How can you push your code to GitHub? 

> **A:**  You can push your code to GitHub only after you've connected your local repository with a remote repository. To link your GitHub repo to your local computer, you want to sync or set up a local repo to point to GitHub repo. The default name is origin (or any name you choose) vs. the long link url of the github repo. Here's how: 
- Before creating a remote repo on Github, make sure to create a new directory with at least one file on your computer. Then make that directory a git repo with git init. Lastly, add and commit files, with git add and git commit.
- Now head over to GitHub site. Create a new repo on GitHub and then type the name of the repo and then after creating repo, you’ll get to a quick setup page. There, you will find commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. 
- Command `git remote add origin <url>`
- Every time you’re making a new github repo, you’re given a url for that repo. All you’ve done with the above command is show where to point this local repository to. 
- Command `git push -u origin main`
- The command above is taking the main branch and pushes it up to origin, where you want this branch to push all the changes to. Here, we've made any changes sync up to the origin. The -u is for upstream, which says that this should be the default repo, the one you should always push to. 
- NOTE: Our GitHub repo name does not have to match with local repo name. Git does not care what the folder name is. So when you're making the repository, you can name it whatever you want. 
- Now, you can do git add and commit changes until you push all of them to github in one package.

---
---

**Q:** How can you fork and clone a repo on GitHub and what do they mean? 

> **A:** Here's how to fork and clone a github repo:
- To fork a github repo, go to the desired repo and there you will find the option at the top right along with the number of times it's been forked (as well as who forked it). Forking means to download a copy, so you’re essentially making your own version of the repo. Your own "fork in the path" 
- Before making any commands to clone, make sure to navigate to the directory that is the parent directory where you'll have the repo and make sure there are no other folders in this directory with the same name and that the parent directory is not git repo. 
- To clone a github repo, copy the url of the github repo for the following command `git clone <url>` to download all of the files in the forked repo. These files will be in a new folder with the same name as the github repo. So this essentially creates a local version of the remote repo. Cloning is the opposite of when we create a repo locally and then push to git. Cloning takes a remote repo and clones it down to your local system and it automatically makes the same connection with github, where you can push any changes you make locally to it. 
- When you clone a github repo, it is your own version, so you can add your own commits.   

---
---

**Q:** What is the .gitignore file?  

> **A:** .gitignore is a file that says you don’t want anything with this name to be added to git. For example, if you do a mass git add, it won’t add certain files. For example, the DS Store file, that’s generally what we would git ignore. A lot of js have Node module in it and JavaScript projects have a node modules folder, and it has tons of third party code in it, code that you're using in your project that you did not write code for but you're essentially using kind of like a plugin for your app. You don't need that to be in your repository. And it's huge in size. And so generally we git ignore these kinds of files/folders as well. Your API keys is also something you would git ignore; it shouldn’t be public.

---
---

**Q:** Can you do repo within a repo and how should you go about naming your repo?

> **A:** When you do a repo within a repo, it's called a sub module pattern where you have modules within modules. It's generally not recommended. If you push the inner repo, it’ll update the inner repo. If you try to add the inner repo to the outer repo, it will send a warning before updating it. The warning lets you know that clones of the outer repo will not have what's inside the embedded repo and will not know how to sync it. And then it gives you instructions on how to add a submodule, if that is the intended goal with the `git submodule add <url> directory` command. If this was done by mistake, you can remove it with `git fm --cached directory` command.
Moreover, you should give your repository a name that is meaningful as opposed to the names GitHub typically suggests, like "curly-rotary-phone." It's also typical to give your repository the same name as the folder that contains your repository on your local machine.


---