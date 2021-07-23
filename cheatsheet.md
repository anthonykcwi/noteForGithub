## Git Cheatsheet

1. Initialize a project
```
$ git init 
```

2. Specify username 
```
$ git config --global user.name ‘Leo Fu’
```

3. Specify password 
```
$ git config --global user.email ‘runrunleorun@gmail.com’
```

4. Add a file to staging area
```
$ git add <filename>
```

5. Add all files with `.html` extension to staging area
```
$ git add *.html
```

6. Add all files to staging area
```
$ git add . 
```

7. Check staging area status
```
$ git status
```

8. Commit from staging to local repository (will be prompted to enter commit message)
```
$ git commit
```

9. Commit from staging to local repository with specified commit message
```
$ git commit -m ‘message’
```

10. (todo: need clarification)
```
$ git remote add origins <url>
```
  
11. Print out remote (todo: need clarification)
```  
$ git remote
```

12. Push master branch form local to remote
```
$ git push -u origin master 
```

13. Pull all changes from remote to local
```
$ git pull
```

14. Clone a project into local
```
$ git clone 
```


15. Show branch
```
$ git branch
```

16. Create a new branch
```
$ git branch <branch name>
```

17. Switch to another branch
```
$ git checkout <branch name>
```

18. Merge a branch to the main/master branch
```
$ git merge <branch name>
```

