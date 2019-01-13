# 分支

## 新增

```

$ git branch <branchName>

```

### 指定版號開啟分支

```

$ git branch <branchName> <versionId>

```

## 檢視

```

$ git branch

```

## 重新命名

```

$ git branch -m <oldName> <newName>

```

## 刪除

```

$ git branch -d <branchName>

// 強制刪除 branch，但只有目前分支不能刪除
$ git branch -D <branchName>

```

## 切換

```

$ git checkout <branchName>

// 若分支存在則切換分之，若不存在則新建
& git checkout -b <branchName>

```