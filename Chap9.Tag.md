# 標籤

用來標示軟體開發的里程碑

## 輕量標籤(lightweight tag)

紀錄少量資料

```

// 將 tag 加在目前 commit 上
$ git tag <tag name>

// 將 tag 加在指定 commit 上
$ git tag <tag name> <commit versionId>

```

## 附註標籤(annotated tag)

能紀錄較多資料

```

$ git tag <tag name> <commit versionId> -a -m "<tag message>"

```

## 刪除

```

$ git tag -d <tag name>

```