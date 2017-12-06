# git-practice
Practice the git operation and command

## git basic command

* git add Readme.md
* git commit -m "commnet"
* git push(git push origin 930)
* git checkout 940
* git pull(git pull origin 940)
* git reset --hard origin/940
* git checkout .(!!!)
* git clean -xdf(f:remove the untracked file; d:directory; x:ignore the .gitignore file restrict)
* git stash save "commemnt"
* git stash list
* git stash apply stash@{1}

## git revert

* git log
* git reset --hard 73554da287bbeb4858ba087e040561764e4ea557
* git push -f

## git merge

* git pull (git pull origin 930)
* git fetch origin 921
* git merge --no-f 921
* //resolve conflict manually
* git add .
* git commit -m "merge code from 921 into 930"
* git push (git push origin 930)



