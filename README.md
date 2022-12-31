# git cheatsheet commands

count unique authors in the repo over the last 30 days
```
git log --since=30.days | grep Author: | sort -u | wc -l
```
