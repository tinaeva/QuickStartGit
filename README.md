# QuickStartGit
1. cd xxx
2. git init
3. git add .     git add -A    
4. git commit -m "xxx"
5. git status
6. git checkout -b new_branch     or:
    git branch new_branch & git checkout new_branch
7. git branch
8. git checkout master
9. git merge new_branch
10. git add.      git commit -m "discard branch"
11. git checkout master (back to before branch)
12. to delete branch(after merge, only delete branch):  git branch -d branch_to_delete     
13. if not merge branch to master, call above will get error msg， need to use force delete:
    git branch -D branch_to_delete
14. roll back to prev version: 
      git log
      git checkout asdfasdfasdf    <- the number after commit
15. add remote repository (first time) :
     git remote add origin https://your_username......
origin is just a name of remote repository, can change name to divide several repos
16. git push [-u] origin master
17. get local copy from remote repo (first time) :
    git clone https://github.com/tinaeva/UnlockLeetCode.git
18. git pull origin master (remember to pull before push)
19. create some shortcut:
    git config --global alias.c 'commit -m'
    git config --global alias.co 'checkout'
    git config --global alias.cob 'checkout -b'
    git config --global alias.br 'branch'
    git config --global alias.m 'merge'
    git config --global alias.a 'add .'
    git config --global alias.s 'status'
    git config --global alias.dbr 'branch -d'
