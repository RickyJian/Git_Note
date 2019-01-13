# 分支合併

將兩個分支做合併

## merge

```

// 現在所在分支為 master，將 <branchName> 合到現在分支(maser)
$ git merge <branchName>

```

## rebase

將現有分支複製並建立在要合併的分支上

```

// 現在所在分支為 master，將 master 建立在 <branchName> 上
$ git rebase <branchName>

```

### 取消 rebase

```

$ git reset <Rebases 前的 VersionId> --hard

```