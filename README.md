# Intro to Git

This is an introduction to Git version control. One of the first things we can do is initialize a git repository.

What does it mean to initialize a git repository?

Let's tun the command `git init` and see what happens.
As you can see, it creates a hidden folder `.git`.
Inside that folder, there is Git code that will keep track of changes to files and folders within this repository.

Git keeps track of the changes.
`HEAD` is the most recent changes.

Another git command that we can use right now is `git status`.
`git status` give us the current status of the repository. In this case since we just created the repo it tells us that there are no commits, and that the README.md is untracked.

In order to track a file, we can tell git to track it, using the `git add <filename>` command, or if we want to track all files, we can use `git add .` or `git add -A`.

q: bring you out
j/k/d/w: up and down
ctrl+c: quit
git -v: version
man git: manual
pwd: show directory
