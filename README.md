xposed
======

clone all sub projects from https://github.com/rovo89 in 1, managed with repo


##initialize the repo, 
**DO NOT** use git clone directly.
```
  repo init -u git@github.com:haobug/xposed.git --repo-url https://github.com/android/tools_repo
```
##clone all repositories in one shot.
```
  repo sync
```
##or work with multi jobs downloading
where '9' value is equal to you cpu core count or that plus 1.
```
  repo sync -j9
```  
**WARNING** with multi jobs, it will be not easy to abort the repo sync via Ctrl + C

