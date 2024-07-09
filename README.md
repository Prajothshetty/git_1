# git_1
EXPERIMENT 1
git init
git clone repolink 
cd reponame 
git add .
git commit -m "message" 
git push

EXPERIMENT 2
git branch feature-branch
git checkout feature-branch
git add .
git commit -m "message"
git push origin feature-branch:main

git add .
git commit -m "message"
git stash
git checkout feature-branch
git stash apply

EXPERIMENT 3
git clone repolink
git branch -v
git checkout -b feature-branch
git branch -v
git rebase origin 
git add .
git commit -m "message"
git rebase origin

EXPERIMENT 4
git add .
git commit -m "message"
git push
git log  —oneline 
git tag  v1.0 (commit id) 
git tag
git push origin v1.0

EXPERIMENT 5
git log --oneline 
git status 
git checkout feature-branch 
git cherry-pick id

EXPERIMENT 6
git log --oneline 
git show (commit id)
//open new terminal //
git log --author=" " --after="(//yesterday date//) "    --before="(//tmr date//)"
git log -n 5
