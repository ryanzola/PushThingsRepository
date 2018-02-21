# newRepository

## How to push a new project to an existing repository with stuff already in it

 1. use the terminal to navigate to your project folder
 2. git init
 3. git remote add *https://github.com/repoOwner/repoName.git*
 4. git pull --rebase origin master
 5. git add .
 6. git commit -m "hotdogs"
 7. git push -u origin master