Git is a distributed version control system.
Git is a free software.

git add <file> : to submit file to Git repository
git commit -m <message> : leave short commit for this change (easy to find and remember what have done)
git status : check repository status
git diff <file> : show the change of file from repo ver. to current ver.
git log (--pretty=oneline) : check commit history
git reset --hard HEAD^ : rollback to the last ver
git reflog : show every command
git restore <file> : discard changes
git restore --staged <file> : unstage
git remote add origin https://github.com/joegusj/Git.git : connect to Github repository
git push -u origin master : push local repo to Github at the first time
git push origin master : push lastest modification to remote repo
git clone 
git checkout -b <branchname> | git switch -c <branchname>: create and switch to <branchname>
git merge <branchname> : merge <branchname> to current branch
git branch -d <branchname> : delete branch
branch conflict-check
