# 版本控管

## 流程

![Status](/images/Status.png)

### Working Directory(工作區)

未被 Git 版控的檔案

```

// 單檔加入 Staging Area
$ git add <fileName>

// 將所有副檔名加入 Staging Area
$ git add <.html>

// 全檔加入 Staging Area
$ git add --all

```

### Staging Area(暫存區)

Git 版控的暫存檔案

```

// 完成版控，將檔案寫入到 Repository
$ git commit -m '<commit message>'

```

### Repository(儲存區)

Git 完成版控所放置的地方

#### amend

修改 commit message，但只能修改最後一個 commit。建議不要在 push 出去後修改 commit 資訊。

```

$ git commit --amend -m "<new message>"

```

## 檢視版控狀態

terminal 會顯示出現在檔案狀態(Working Directory、Staging Area、Repository)

```

$ git status

```

## 檢視版控紀錄

```

// 檢視 log 以文字顯示
$ git log

// 檢視 log 以圖形方式顯示
$ git log --oneline --graph

// 以 commit 作者來搜尋 commit 的紀錄
$ git log --oneline --author="<auther name>"

// 以 commit訊息 來搜尋 commit 紀錄
$ git log --oneline --grep="<message>"

// 搜尋 commit 檔案內容
$ git log -S "<message>"

// 檢視檔案紀錄
$ git log <fileName>

// 檢視檔案異動內容
$ git log -p <fileName>

```

### blame

檢視內容每行異動紀錄

```

$ git blame <fileName>

```

## 解除檔案版控

```

$ git rm <fileName> --cached

```

## 改名

```

$ git mv <oldFileName> <newFileName>

```

> git 當檔名一樣時不會區分大小寫