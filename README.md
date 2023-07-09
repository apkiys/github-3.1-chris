# github-3.1-chris
This is the assignment for Module 3.1

-----------------------------------------------------------------

# Assignment for Module 3.1
### _Github Commands I have learnt_
[![GitHub](https://logosmarcas.net/wp-content/uploads/2020/12/GitHub-Simbolo.png)](https://github.com/apkiys/github-3.1-chris)

The following are the commands I have used in familiarising with Git and GitHub:

#### Git/GitHub Linking
- (Link to GitHub credentials) git config --global user.email "*****@******"
- (Link to GitHub credentials) git config --global user.name "******"

#### Repository Creation
- (Create remote repository in GitHub) gh repo create github-3.1-chris --public --description 'This is the assignment for Module 3.1' --add-readme
- (Download repository into local) git clone git@github.com:apkiys/github-3.1-chris

#### Remote Repository Pull
- (Checking remote without merging into local) git fetch git@github.com:apkiys/github-3.1-chris
- (Download and merges into local) git pull git@github.com:apkiys/github-3.1-chris

#### Repository Branch
- (Create and change to new branch) git checkout -b feature-2
- (List all branches) git branch
- (Switch to main branch) git checkout main
- (Delete newly created branch) git branch -D feature-2

#### Local Repository Push
- git add .
- git commit -m 'Create changes on README file'
- git push origin main

#### Reference:
- https://dillinger.io/