# GitAndGithub
## Show the git configurations
```git
git config --list
```

## Set the user name
```git
git config --global user.name "your user"
```

## Set the email
```git
git config --global user.name "your email"
```

## Check the git status
```git
git status
```

## Start the trac of a or multiple file
```git
git add --all          [all files]
or
git add .              [all files]
or
git add test.txt       [ Specific file ]
```
## Git commit
```git
git commit -m ""
```

## Check git log
```git
git log
git log --oneline
git log --oneline --graph
git log --oneline --graph --all
```

## If you want to revert previos any commit.
```git
git reset --hard 1ec7739
```

## Show all reference log
```git
git reflog
```
## Remove a file from git track
```git
git rm anyfile
```

## Show all branch
```git
git branch --list
```

## Create a branch
```git
git branch dev/add-heading-text
```

## Switch a branch
```git
git switch dev/add-heading-text
```

## Marge 2 branch. My current branch is "dev/add-heading-text". I want to marge with main branch
```git
git switch main
git merge dev/add-heading-text
```

## Branch delete
```git
git branch -d dev/add-heading-text
git branch -D dev/add-heading-text    [Fource delete, without any info]
```

## Branch name change. I want to change the "dev/add-heading-text" branch name.
```git
First switch the dev/add-heading-text branch
git switch dev/add-heading-text
git branch -m feature/add-headding-text

git branch --list
```

## Marge conflict

## Git stash

## Git ignore file
```git
git rm --cached test.js
```

## Pull request

## Gir forking

git diff test.js
