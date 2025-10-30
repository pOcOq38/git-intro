# Introduction to Git

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

And to save, in git we use the `git commit` command.
So, lets make our first commit!

```
git commit -m 'Initial commit'
```

## Sharing with Github

Now I'm going to add a remote repo. This is just a way to share code with a central code directory that others can access as well. In this case, we'll use Github.
Go to github, create a new repository, and add it to your project with the `git remote` command.

```
git remote add origin <github-repository-url>
```

Now that we have a remote repository and a remote set up, we can push out code to it.

Let's make another commit, and then push our code using the following:

```
git push github <branch>
```

## Git branches

Let's start by creating a new `feature/javascript` and we'll add a folder with some HTML and JavaScript to run in out browser.

```
git branch feature/javascript
git checkout feature/javascript
```

or in one line

```
git checkout -b feature/javascript
```

And let's creat an HTML web page with som JS that sends an alert to say "Hello World!"

Git tracks only files. When tracking the folder, make the hidden file inside the folder.

### Commands

```
q: bring you out
j/k/d/w: up and down
ctrl+c: quit
git -v: version
man git: manual
pwd: show directory
git help: git help log, git help commit etc
git diff: show differences
git log --oneline: show log in one line
git checkout -: "-" means previous
```
