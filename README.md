# Assignment5
## Name and date:
Jakub Stach, 11/22/2025
## List of useful commands:
### initialization
- git clone < repository >
    - Clone a repository into a new directory
- git pull < repository >
    -  Fetch from and integrate with another repository or a local branch
- git init 
    - Create an empty Git repository or reinitialize an existing one
- git add < filename >
    - Add file contents to the index
- git add .
    - Add all files contents to the index
- git rm < filename >
    - Remove files from the working tree and from the index
### branches
- git branch    
    - List branches
- git branch < branch >
    - Create new branch
- git branch -D < branch >
    - Delete branch
- git checkout < branch >
    - Switch to a branch
- git merge < branch >
    - Join two development histories together
### update
- git commit -m "< message > " Record changes to the repository
    - Record changes to the repository
- git push < repository > < branch >
    - Update remote refs along with associated objects
### revisions
- git diff < commit1 > < commit2 >
    - Show changes between commits
- git diff < branch1 >..< branch2 >
    - Show changes between branches
- git log 
    - Show commit logs
- git status
    - Show the working tree status