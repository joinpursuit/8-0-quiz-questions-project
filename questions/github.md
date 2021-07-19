# GitHub


**Q:** How are git and github related? 

> **A:** - With Github, it’s about managing a team and the whole repository vs git where you’re focused on adding and committing changes. Git is open sourced (all the code is available on GitHub), while GitHub is a commercial enterprise (not open source) and the web app is owned by Microsoft. Some of it is open source but it’s a commercial product.  

In GitHub, it's where the main project is housed. It's a backup and a file management system. It's also like a social media where you can contribute and provide comments. Get pull requests if anyone wants to make a change in main repo. 

There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. But github provides it for you after you fork a repo and work on cloning it. 



---
---

**Q:** What is the .gitignore file?  

> **A:** .gitignore is a file that says you don’t want anything with this name to be added to git. For example, if you do a mass git add, it won’t add certain files. For example, the DS Store file, that’s generally what we would git ignore. A lot of js have Node module in it and JavaScript projects have a node modules folder, and it has tons of third party code in it, code that you're using in your project that you did not write code for but you're essentially using kind of like a plugin for your app. You don't need that to be in your repository. And it's huge in size. And so generally we git ignore these kinds of files/folders as well. Your API keys is also something you would git ignore; it shouldn’t be public.

---
---

**Q:** Can you do repo within a repo and how should you go about naming your repo?

> **A:** When you do a repo within a repo, it's called a sub module pattern where you have modules within modules. It's generally not recommended. You should give your repository a name that is meaningful as opposed to the names GitHub typically suggests, like "curly-rotary-phone." It's also typical to give your repository the same name as the folder that contains your repository on your local machine.


---