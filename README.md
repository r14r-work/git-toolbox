# git-toolbox

# Basics

## Create from command line
    echo "# bash-toolbox" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/$GITHUB_USR/$GITHUB_REP.git
    git push -u origin master

## Push an existing repository from the command line
    git remote add origin https://github.com/$GITHUB_USR/$GITHUB_REP.git
    git push -u origin master
