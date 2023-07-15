# Working with Git and GitHub
## 1. Checking the existance of Git
Type in terminal `git version`
If Git is installed, the message will show the version of the Git. 
Othewise it ruturn the error.
## 2. Git installation
Load the latest version of Git from the site (git-scm.com/downloads).
Install it with the default settings.
## 3. Git configuration
When you launch Git the first time, you need to introduce yourself by typing 2 following lines:
```
git config --global user.name "Your name"
git config --global user.email "Your email"
```
## 4. Initializing repository
In the terminal, navigate to the folder where we want to create the repository.
And run the command:
```
git init
```
## 5. Commiting the changes in the repository
After modifying some file(s), use this command to stage the changes you want to include in the commit:
```
git add <file>
```
To add all modified files:
```
git add .
```
Once changes are stages, they are ready to be committed.
To create a new commit with the staged changes, run the following command:
```
git commit -m "Commit message"
```
## 6. Checking the logs of the commits
To view the commit history and logs, run this command:
```
git log
git log --oneline
```
## 7. Switching between the commits
After you obtained the commit hash of the desired commit by checking the logs, run the following command:
```
git checkout <commit-hash>
```
In order to switch to the 'master' branch, run:
```
git checkout master
```