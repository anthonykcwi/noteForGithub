## Git Cheatsheet

1. Create a new local repository
```
$ git init 
```

2. Tell Git what author name to be used with your commits.
```
$ git config --global user.name ‘Leo Fu’
```

3. Tell Git what email address to be used with your commits. 
```
$ git config --global user.email ‘runrunleorun@gmail.com’
```

4. Add a single file to staging area
```
$ git add <filename>
```

5. Add all files with `.html` extension to staging area
```
$ git add *.html
```

6. Add all files to staging area
```
$ git add * 
```

7. List the files that you have changed and those you still need to add or commit
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

10. If you haven't connected your local repository to a remote server, add the server to be able to push to it
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

19. Drop all your local changes and commits,
fetch the latest history from the server, and 
point your local main branch at it.
```
$ git fetch origin 
$ git reset --hard origin/master
```
