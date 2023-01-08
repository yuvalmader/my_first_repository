# Learning Git

Important steps for git workflow:

1. Initialize repository with git init
2. Create changes to project files 
3. Check status of those files with git status (git status)
4. Stage changes for commit (git add)
5. Commit changes to version history (git commit -m "message insterted here")
6. Review previous changes with git log (git log --oneline --> gives concise info | git log --stat --> gives statistics)
7. If you need to ammend most recent message, so long as working tree is clear in git status, you can use git commit --amend 

BRANCHING 
1. git branch (let's you know on which branch you are, marked by *) 
2. git checkout NameOfBranch (allows you to switch to the branch you want) 
3. git checkout -b NameOfNewBranch (allows you to move over to a new branch and create it) 
4. git branch -d (or -D) NameOfBranch (allows you to delete a branch)
5. git merge NameOfBranch (to merge the new branch's updates to the main branch)


