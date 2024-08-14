# git-commands

##### To move the HEAD for n of commits then squash these commits into a single meaningful commit.
> git reset --hard HEAD~<n> <br>
> git merge --squash HEAD@{1}
##### To display list of files added or modiifed in a given commit.
> git diff-tree <commit_hash>
##### To add all modified files to staging area then commiting them with a message.
> git commit -a -m "Refactor code base"
##### Force overwrite the files from a remote branch
>  git fetch --all
>  git reset --hard origin/master
