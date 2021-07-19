# History

Make sure you are located in the `8-0-quiz-questions-project/` directory on the command line. Then, run the following command.

```bash
history | tail -n 50 >> history.md
```

The command above will add the last 50 lines you ran to the end of this file. If something goes wrong, feel free to delete everything below the three dashes below.

---

➜  Documents Pursuit
➜  Pursuit Module-1\
➜  Module-1  07-15-21
➜  07-15-21 8-0-quiz-questions-project
➜  8-0-quiz-questions-project git:(main) ✗ code .
➜  8-0-quiz-questions-project git:(main) ✗ ls
history.md questions  readme.md  rubric.md  topics.md
➜  8-0-quiz-questions-project git:(main) ✗ questions
➜  questions git:(main) ✗ ls
Arrays-and-Objects.md Functions.md          example.md
➜  questions git:(main) ✗ git add Functions.md
➜  questions git:(main) ✗ git commit -m "functions questiosn."
[main bbf63ff] functions questiosn.
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 47 insertions(+)
 create mode 100644 questions/Functions.md
➜  questions git:(main) ✗ git add Arrays-and-Objects.md
➜  questions git:(main) ✗ git commit -m "Arrays & Objects."
[main ac3ef5a] Arrays & Objects.
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 72 insertions(+)
 create mode 100644 questions/Arrays-and-Objects.md
➜  questions git:(main) ✗ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 2.34 KiB | 2.34 MiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/EvaRodCor/8-0-quiz-questions-project.git
   b11987c..ac3ef5a  main -> main
➜  questions git:(main) ✗ touch Loops.md
➜  questions git:(main) ✗ git add Loops.md
➜  questions git:(main) ✗ git commit -m "Loops Questions."
[main 04b8c66] Loops Questions.
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 questions/Loops.md
➜  questions git:(main) ✗ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 341 bytes | 341.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/EvaRodCor/8-0-quiz-questions-project.git
   ac3ef5a..04b8c66  main -> main
➜  questions git:(main) ✗ git add Loops.md
➜  questions git:(main) ✗ git commit -m "Loops Questions."
[main 7ba559e] Loops Questions.
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 98 insertions(+)
➜  questions git:(main) ✗ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.72 KiB | 1.72 MiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/EvaRodCor/8-0-quiz-questions-project.git
   04b8c66..7ba559e  main -> main
➜  questions git:(main) ✗ touch git.md
➜  questions git:(main) ✗ git add git.md
➜  questions git:(main) ✗ git add git.md
➜  questions git:(main) ✗ git commit -m "Git Questions"
[main 8157291] Git Questions
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 24 insertions(+)
 create mode 100644 questions/git.md
➜  questions git:(main) ✗ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.00 KiB | 1.00 MiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/EvaRodCor/8-0-quiz-questions-project.git
   7ba559e..8157291  main -> main
➜  questions git:(main) ✗ touch GitHub.md
➜  questions git:(main) ✗ git add GitHub.md
➜  questions git:(main) ✗ git add Github.md
➜  questions git:(main) ✗ git commit -m "GitHub Questions"
[main 04ad508] GitHub Questions
 Committer: Eva Rodriguez <evarodriguez@Evas-MBP.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 20 insertions(+)
 create mode 100644 questions/GitHub.md
➜  questions git:(main) ✗ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 916 bytes | 916.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/EvaRodCor/8-0-quiz-questions-project.git
   8157291..04ad508  main -> main
➜  questions git:(main) ✗ ~


<p>&nbsp;</p>

>*Dear Staff I was trying to use my history command on my Terminal but for whatever reason it just stopped working I probably wrote it wrong but now I can't get out of it and I did't want to lose my history so I pasted all I did so you guys can see I did use all the commands. I'm very sorry for the inconvinience.*