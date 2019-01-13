# 遠端

git 分為本地端及遠端

## 新增

本地可以有多個遠端

```

// 預設遠端名稱通常使用 origin 
$ git remote add <remote name> <url>

```

## 檢視

```

$ git remote -v

```

## 推送

將本地資料推到遠端，每個分支只能指定一個上游。建議在上版前先將遠端 pull 下來

```

$ git push -u <remote name> <branch name>

```

## 下載

將上游資料擷取到本地端

```

$ git fetch <remote name>

```

## 下載並合併

將上游資料擷取到本地端並合併

```

$ git pull <remote name>

```

## Clone()

將專案由遠端複製到本地端，目的是在初始本地端專案

```

$ git clone <remote url or ssh>

```