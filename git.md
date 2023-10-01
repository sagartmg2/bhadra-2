
<!-- initial setup  -->

1. git init
2. git remote add origin https://github.com/sagartmg2/bhara-2
        to check
            git remote -v

<!-- day to day  -->
1. git status  ( optional )
2. git add
    - git add score.html  //  individual file 
    - git add . // all files at once
3. git commit -m "hint/message"
4. git push



<!-- to pull codes -->
    git pull   NOTE: there should not be changes left to commit
               Beware of merge confitscts..


<!-- branches -->
    usually created for new features]

    git branch   // view current branch we are in 
    git branch -r  // view remote / online branches
    git fetch // to sync  // sync number of commits,   branches

    git checkout -b auth // to create new branch
    git checkout <branch_name>

