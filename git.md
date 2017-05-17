# Git commands

## Show configuration
```
git config -l
```

## Set your identity
```
git config --global user.name "Eson Paguia"
git config --global user.email hi@esonpaguia.com
```

## Set proxy
```
git config --global http.proxy http://142.174.134.33:8080
git config --global https.proxy https://142.174.134.33:8080
```

## Unset proxy
```
git config --global --unset http.proxy
git config --global --unset https.proxy
```

## Force http:// instead of git://
```
git config --global url."https://".insteadOf git://
```

## Unset http:// instead of git://
```
git config --global --unset url."https://".insteadOf git://
```

## Clone
```
git clone https://github.com/esonpaguia/cheatsheets.git
```

## List local branches
```
git branch -v
```
```
git branch -vv
```

## List remote branches
```
git branch -r
```

## List remote repositories
```
git remote -v
```

## Show details of remote
```
git remote show origin
```

## Create a new local branch
```
git checkout -b 2016.04.dev
```

## Push local branch to remote
```
git push -u origin 2016.04.dev
```

## Set upstream
```
git checkout -b test
git branch --set-upstream origin/2016.04.dev
```

## The usual
```
git clone https://github.com/esonpaguia/cheatsheets.git
git status
git add --all
git commit -m "Message here"
git push
```
```
git init
git add --all
git commit -m "Message here"
git remote add origin https://github.com/esonpaguia/cheatsheets.git
git push
```

## Merge to master
```
git checkout master
git merge 2016.04.dev
git push
```

## Remove a local branch
```
git branch -D 2016.04.dev
```

## Remove a remote branch
```
git push origin :2016.04.dev
```

## Create a tag
```
git checkout master
git tag 2016.04.rls.1
git push --tags
```

## List tags
```
git tag
```

## Rename a tag
```
git push origin <old-tag>:<new-tag> :<old-tag> && git tag -d <old-tag>
```

## Show history
```
git log --graph --oneline --decorate
```

## Show files for specific commit
```
git diff-tree --no-commit-id --name-only -r [commit_id]
```
