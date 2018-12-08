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

    ##
    git branch -f bugFix HEAD~3
    git checkout C6
    git branch -f master HEAD~0
    git checkout C1

    ##
    git reset HEAD~1
    git checkout pushed
    git revert HEAD

- - - - - - - -

#3 Moving Work Around

    ## Cherry-pick Intro
    git cherry-pick <Commit1> <Commit2> <...>
    git cherry-pick C3 C4 C7
    
    Git cherry-pick is great when you know which commits you want (and you know their corresponding hashes)
    
    ## git rebase -i HEAD~4

- - - - - - - -

#4 A Mixed Bag

    ## 1: Grabbing Just 1 Commit
    git rebase -i HEAD~3
    git checkout master
    git cherry-pick C4
    
    ## 2: Juggling Commits

