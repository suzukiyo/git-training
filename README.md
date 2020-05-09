**これだけで開発の8〜9割が事足りる。**

## 基本編

### 初期化する
```
git init
```

### クローン(コピー)する
```
git clone git@github.com:userName/repositoryName.git
```

### チェックアウトする
```
git checkout -b feature/hogehoge
```

### 状態を確認する
```
git status
```

### 最新にする
```
git pull
```

### インデックスに登録する
```
git add .
```

### 戻す
```
git reset HEAD
git reset HEAD core/src/main/resources/application.properties
git reset --soft HEAD~
git reset --hard #コミットid
```

### コミットする
```
git commit -m "fix: refactoring shopping cart controller"
```

### コミットを変更する
```
git commit --amend
```

### 反映する
```
git push
```

## 番外編

### 一時保存する
```
git stash
```

### ブランチを削除する
```
git branch -d feature/hogehoge
```

### ログを見る
```
git log --graph
```