# Quiz Questions Project

In this course, you're quizzed often after being taught a new concept. That's because one of the best ways to retain knowledge is to be constantly asked to recall information.

In this project, you'll be asked to come up with your own quiz questions for a number of different topics. You'll also be asked to provide the answers and explanations. You can then use these questions to quiz yourself and your classmates.

Throughout the process, you'll be asked to make use of the Command Line, VSCode, git, and GitHub.

## Instructions

### Getting started

1. Fork and clone this repository.

1. Open the repository with VSCode.

### Project overview

To complete this assignment, do the following.

View the [topics.md](./topics.md) file in this repository. A series of topics will be listed in it.

For each topic, create a new Markdown file in the `questions/` folder from the command line. Use proper casing for your filenames. For example, if the topic is "Introductory JavaScript", your file should be named `introductory-javascript.md`.

In each of those files, you will add questions, answers, and explanations. For an example, see the [example.md](./questions/example.md) file.

For each topic, include _at least_ three questions. Once you have completed the base requirements, you are welcome to include more questions, topics, or both.

You may use your notes or research from the internet to answer questions. However, you should not copy and paste answers and questions from the internet directly.

Whenever you finish questions for a topic, add the new file you created and create a new commit. Then, push you changes to GitHub. Use sensible commit messages.

Finally, you will need to run a command inside of the repository that will capture the last few lines you ran in your terminal. This will be how we assess your ability to use the command line for this project. (For more instructions on this, see the [history.md](./history.md) file.)

This project will be graded against a rubric. To view the rubric, you can look at the [rubric.md](./rubric.md) file.

### Tasks

The following is a shorter checklist of the Overview above.

- [x] Open the [topics.md](./topics.md) file and look over the topics.

For each topic:

- [x] Create a Markdown file in the `questions/` directory with the topic name.

- [x] Add _at least_ three questions to the Markdown file, with answers and an explanation. (For an example, see the [example.md](./example.md) file.)

[x] Functions
[x] Arrays & Objects
[x] Loops
[x] Git
[x] GitHub

- [x] Once you're done with a topic, commit your changes.

- [x] Then, push those changes to GitHub.

At the very end:

- [x] Follow the instructions in the [history.md](./history.md) file.

- [x] Add and commit the changes caused by following the instructions in that file with the following commit message:
  ```
  Updated history.md file.
  ```

### Submitting

Once you've completed all the work, create a Pull Request against this repository.

## Tips on writing good questions

Questions that require you to recall more information are generally better questions. For example, imagine you are trying to recall information about different data types in JavaScript.

The following is a good question.

> Is "Number" one of the data types in JavaScript?

While this checks for some amount of understanding, it gives away the answer in the question.

A better question would be the following.

> The value `9` is what data type in JavaScript?

This requires the person answering the question to recall the name of the data type.

The two questions above get at a specific answer, but even better questions require you to synthesize multiple ideas and recall multiple pieces of information.

> What are the five most common data types in JavaScript? Give an example of each.

The above gives away little information in the question and requires the person answering to recall a lot of information. That's good!

Finally, questions can be even more powerful if context is given around them.

> Imagine you are writing an algorithm that checks to see whether or not a password is too short. What data types do you think would be present in the algorithm?

The question above requires the person answering the question to think critically and choose among multiple data types in order to solve a specific problem. The question above is the kind of question you could be asked on an interview, because it requires a high level of knowledge about the given topic.
