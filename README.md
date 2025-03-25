# Git Commands
Git is an open surce distrinted version control system.

## The stages of git
https://www.google.com/imgres?q=tell%20me%20about%20git&imgurl=https%3A%2F%2Fwww.simplilearn.com%2Fice9%2Ffree_resources_article_thumb%2Fbusiness.JPG&imgrefurl=https%3A%2F%2Fwww.simplilearn.com%2Ftutorials%2Fgit-tutorial%2Fwhat-is-git&docid=4dCPYscVJt2OeM&tbnid=Nm3MnwmzCh74XM&vet=12ahUKEwjIg-7bsaWMAxXcSkEAHWiXGFYQM3oECGUQAA..i&w=567&h=369&hcb=2&ved=2ahUKEwjIg-7bsaWMAxXcSkEAHWiXGFYQM3oECGUQAA

- The Workspace : This is where unstaged files are located
- The Staging Area : This is where files go to after they have been staged
- The Commit/Local Rep : This is Where the commited files are saved as aversion
- The Remote Repo : This is where the pushed local repo are stored remotely

## The Commands
### Initialized a Repo
To initialized  a repo for an exixting project,
- navigate to the working dir of the project ou want to initialize  and use the command `git init`
```sh
cd <project-di>

```
- Create a repo on github and use the command `git clone` to clone the repo locally and begin your project
```sh
git clone <repo-url>
```

### Checking the status of our files
To check the staus of your files, you use command `git status`, this will show you if your files are untracked, stages and ready for committing
```sh
git status
```

### Commiting of the files
To commit all files we use the command `git commit`, it will commit your files to github.
```sh
git commit -m "commit to you"
```
 