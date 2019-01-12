# 檢視目錄或檔案紀錄

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

## blame

檢視內容每行異動紀錄

```

$ git blame <fileName>

```
