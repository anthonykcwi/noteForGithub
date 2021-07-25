## What is fast-forward merge?

1. This document explains what fast-forward merging is. It also gives 
example of doing fast-forward merge. 

2. This file (`fast_fwd_merge.md)` is the main entry point. Besides, it
may contains image files and other files that may help to describe the 
topic. 

3. Create a new branch called fast-forward

   `$ git branch fast-forward`

4. Switch branch from master to fast-forward
``
$ git checkout fast-forward
``

5. Create and add the file to local

   `touch fast-forward.md
   git add fast-forward.md`

6. Continue editing the file 

7. When finish, commit the file to staging area 

   `$ git commit fast_forward.md -m "fast_forward.md initial commit"`

8. Continue editing the file until finish. You may or may not have 
multiple commit in between. 

9. Before fast-forward merge, run git status to be sure all changes are committed 

   `$ git st` 
   `On branch fast-forward` 
   `nothing to commit, working directory clean`

10. Switch to master branch 
    `` 
    $ git checkout master 
    ``

11. Merge changes from fast-forward branch into the master branch 

    `$ git merge fast-foward` 

12. You have essentially moved the pointer for the master branch forward 
    to the current head 

13. Push changes to remote repository 

    `` 
    $ git push origin master 
    ``

14. That's it. 





