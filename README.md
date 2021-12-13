# git-commands
test for git commands

commands : 


Create branch:
----------------
git checkout -b newb main  



delete branch local and remote
-------------------------------
git push origin --delete newb



delete local branch only
-------------------------
git branch -d newb


merge
------
- git checkout main
- git merge newb
- git push

error: The following untracked working tree files would be overwritten by checkout:
You can try command to clear the untracked files from the local
------------------
- git clean -d -f .
