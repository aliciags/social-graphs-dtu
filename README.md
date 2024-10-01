# SOCIAL GRAPHS AND INTERACTIONS

## How to create a branch
``` bash
git checkout -b <branch-name>
```

## How to switch branches
``` bash
git checkout <branch-name>
```

## Pull changes from main to working branch
``` bash
git checkout main
git pull
git checkout <branch-name>
git merge main
# EDIT CODE
# IF NEW FILES CREATED
git add .
# IF NO NEW FILES DIRECTLY
git commit -a -m “message”
git push
# CHECK EVERYTHING UPLOADED CORRECTLY
git status
# THEN FROM GITHUB CREATE A PULL REQUEST TO MAIN
```

## How to undo last commit before pushed
``` bash
git reset --soft HEAD~1
```
