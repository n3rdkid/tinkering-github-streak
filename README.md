# tinkering-github-streak
Testing out GitHub Actions



Trying to make an epic streak using a cron job to make one auto commit a day at 17:17, but due to GitHub Actions cron job running with delays it often runs hour later.


INCASE SOME DAYS GITHUB ACTIONS GOES DOWN
```
https://leewc.com/articles/making-past-git-commits/

$ export GIT_{AUTHOR,COMMITTER}_DATE="YYYY-MM-DD HH:MM:SS"
$ git commit -am 'Commit Message Here'
$ unset GIT_{AUTHOR,COMMITTER}_DATE
```