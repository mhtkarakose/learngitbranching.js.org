#1: Introduction Sequence
    
    ## Git Commits
     git commit

    ##Git Branches
    git checkout -b bugFix

    ##Branches and Merging
    git checkout -b bugFix
    git commit
    git checkout master
    git merge

    ##Git Rebase
    git checkout -b bugFix
    git commit
    git checkout master
    git commit
    git checkout bugFix
    git commit
    git rebase master

- - - - - - - -

#2 Ramping Up

    ##HEAD
    HEAD always points to the most recent commit which is reflected in the working tree. 
    git checkout C4^
