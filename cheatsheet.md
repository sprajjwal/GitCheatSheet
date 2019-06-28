### 1.) Cloning in a github repo

`git clone <URL>`

### 2.) Setting default username and password

`1. vim ~/.netrc`
`2. add this:`
>  `machine github.com`
>> ` login <username>`
>> ` password <password>`

### 3.) Steps to make a directory into a git repo

`1. cd into the folder`
`2. git init`
`3. git add .`
`4. git commit -m "git setup"`
`5. git remote add origin <URL>`
`6. git push origin master`

### 4.) Other Git/GitHub commands

`1. git branch` shows all branches
`2. git push origin <branch_name>` pushes your current commit to this branch
`3. git pull origin <branch_name>` pulls from given branch from GitHub
`4. git checkout <branch_name>` switches to a different branch
`5. git rm ${file}` removes a file and stops tracking
`6. git checkout -b <new_branch_name> ` creates a new branch
`7. git log` shows all the versions with their sha key
`8. git revert ${sha_key}` reverts a commit/ deletes the version and goes to the one before 
`9. git revert HEAD` reverts the latest commit