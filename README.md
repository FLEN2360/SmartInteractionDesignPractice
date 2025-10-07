# 智慧互動設計實務

## git 、 git hub

https://github.com/FLEN2360/SmartInteractionDesignPractice/tree/master

### git init

對當前資料夾創建 git 控制
```git
git init
```

### git status

查看目前資料夾狀態
```git
git add status
```

### git add

全部加入暫存區
```git
git add .
```

指定加入暫存區
```git
git add ./{要 add 的檔案路徑}
```

### git config

設定全域使用者名稱、信箱。
```git
git config --global user.name "你的名字"
git config --global user.email "你的Email"
```

查看目前設定。
```git
git config --list
```

### git commit

提交
```git
git commit -m "{提交訊息}"
```

### git log

查看提交歷史紀錄
```git
git log
git log --oneline
```

### git diff

查看尚未暫存的變更
```git
git diff
```

查看已暫存的變更
```git
git diff --staged
```

### git rebase

合併提交
```git
git rebase -i HEAD~2
```

### git branch

查看本地分支
```git
git branch
```
建立新分支
```git
git branch {新分支名稱}
```

#### git checkout

切換分支或回去某個提交
```git
git checkout {分支名稱或提交 ID}
```

#### git merge

目前的分支合併另一個分支
```git
git merge {另一個分支}
```

### git reset

完全保留變更
```git
git reset --soft {提交 ID}
```

部分保留變更
```git
git reset --mixed {提交 ID}
```

完全清除變更
```git
git reset --hard {提交 ID}
```

### git stash

暫存當前目錄
```git
git stash
```

還原暫存
```git
git stash pop
```
### git pull

將檔案從遠端抓取下來
```git
git pull
```

### git push

提交推送（上傳）到遠端
```git
git push
```

強制推送（上傳）到遠端
```git
git push -f
```
### 加一個程式碼
``` js
let RAM;

RAM = 3;
console.log(RAM);


RAM = 2;
console.log(RAM);
```

