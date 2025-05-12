# Setup With Git


```
git init
git remote add origin https://github.com/reactivepixel/git-demo-time.git

```

## Git Notes

```
git branch
git add -A
git status
git commmit -m "message"
git push origin master
git checkout -b new-branch
git checkout master
```

## Workflow process

Add a new feature and add back to dev
```
git checkout dev
git checkout -b feature-name
// do code
git add -A
git commit -m "message"
git checkout dev
git merge feature-name
```

Share our code with others
```
git checkout dev
git push origin dev
```