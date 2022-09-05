## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
A software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.
2. What is the difference between Git and GitHub?
Git is a distributed version control system for tracking changes in source code during software development, whereas GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management functionality of Git as well as adding its own features.
3. Why do we create a branch?
Creating a branch allows for testing and developing in a separate place while leaving the master branch untouched.
4. What is the purpose of a Pull Request?
To review the changes in the code made by a contributor before attempting to merge it into a project.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The git fetch command downloads commits, files, and refs from a remote repository into your local repo.
The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
7. What is a merge conflict?
A merge conflict is when two branches are trying to merge, and both are edited at the same time and in the same file, Git won't be able to identify which version to take for changes.
8. How do you resolve a merge conflict?
To resolve the conflict, it is necessary to know whether the conflict occurs and why it occurs. The "git mergetool" command is used to resolve a merge conflict.
