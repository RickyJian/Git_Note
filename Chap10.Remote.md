# 遠端

git 分為本地端及遠端

## 新增

```

// 預設遠端名稱通常使用 origin 
$ git remote add <remote name> <url>

```

## 推送

將本地資料推到遠端，每個分支只能指定一個上游。建議在上版前先將遠端 pull 下來

```

$ git push -u <upstream name> <branch name>

```

## 下載

將上游資料擷取到本地端

```

$ git fetch

```

## 下載並合併

將上游資料擷取到本地端並合併

```

$ git pull

```