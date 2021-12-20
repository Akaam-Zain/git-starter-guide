# git-starter-guide

This is a starter guide and cheatsheet to maintain a Git Repo.

## GIT FLOW

master -> release 1 feature 1
release 2. -> develop -> feature 2
release 3. epic -> feature 1
feature 2

## CHEATSHEET

1. **git add** - stages
2. **git commit** - locally commits
3. **git push** - pushes to remote repo
4. **git fetch** - pulls from remote but does not merge
5. **git pull** - pulls from remote and tries to merge
6. **git rebase** - not understood <preferred not to use>
7. **git remote add <remote-id> <remote-url>** - add remote repo
8. **git checkout <branch-name>** - switches branch
9. **git switch <branch-name>** - switches branch
10. **git checkout - - <filename>** : undos all changes in that file (applies only if not committed)
11. **git stash** : undo all file changes
12. **git reset - - hard <commit-id>** : reverts code back to the commit
13. **git revert <commit-id>** : undos the commit and changes file (removes any changes done)
14. **git log** : shows git commit history

CommitLint comment practices

- build
- ci
- chore
- docs
- feat
- fix
- perf
- refactor
- revert
- style
- test
