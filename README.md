**This alone is enough for 80 to 90% of the development.**

## general

### initialize
```
git init
```

### clone(copy)
```
git clone git@github.com:userName/repositoryName.git
```

### checkout(move)
```
git checkout -b feature/hogehoge
```

### confirm status
```
git status
```

### update
```
git pull
```

### register index
```
git add .
```

### return
```
git reset HEAD
git reset HEAD core/src/main/resources/application.properties
git reset --soft HEAD~
git reset --hard #commitId
```

### commit
```
git commit -m "fix: refactoring shopping cart controller"
```

### modify commit
```
git commit --amend
```

### reflect
```
git push
```

## others

### temporary save
```
git stash
```

### delete branch
```
git branch -d feature/hogehoge
```

### show log
```
git log --graph
```