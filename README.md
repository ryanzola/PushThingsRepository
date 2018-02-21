# newRepository

### How to push a new project to an existing repository with stuff already in it

 1. use the terminal to navigate to your project folder
 2. `git init`
    - Create an empty Git repository or reinitialize an existing one
 3. `git remote add origin https://github.com/repoOwner/repoName.git`
    - Link this folder with the github repository
 4. `git pull --rebase origin master`
    - performs a git pull and git rebase on a tracking upstream
 5. `git add .`
    - add the folder contents to the index
 6. `git commit -m "hotdogs"`
    - record changes to the repository, with a message about the commit
 7. `git push -u origin master`
    - Update remote refs along with associated objects
    - -u: For every branch that is up to date or successfully pushed, add upstream (tracking) reference, used by argument-less git-pull and other commands.