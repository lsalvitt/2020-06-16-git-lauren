# 2020-06-16 Git

## Local

- `git init`: create a git repository in the current directory
- `git status`: tells you what is going on
- `git add <filename>`: will put files <filename> in the staging area
- `git commit`: will save the staged content as a new commit in the local repository
- `git log`: shows teh hitory of commits we have done
	-`git log --oneline`: shows a shorter online version of `git log`
- `git diff <filename>`: displays difference between commits
- `git checkout xxxxxxx <filename>`: recovers old versions of files, need first 7 digits of version
- `git diff HEAD ~1`: will compare with first previous version. Can change this number to compared versions further back, or use the version 7 digit code.
 
## Remotes

- `git remote add <name> <url>`: gives the remote URL a short name
- `git push <where> <what>`: takes the master branch on your computer and pushes it to the origin
