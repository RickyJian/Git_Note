# 回復

## Reset

把目前狀態設定成某個 commit

### mixed

預設參數，`working directory`不變`Staging Area`丟掉，拆出來的檔案會放置在`working directory`

```

// 退回到上一個 commit
$ git reset --mixed

// 退回到指定的版號
$ git reset --mixed <versionId>

```

### soft

`working directory`不變`Staging Area`不變，拆出來的檔案會放置在`Staging Area`

```

// 退回到上一個 commit
$ git reset --soft

// 退回到指定的版號
$ git reset --soft <versionId>

```

### hard

`working directory`丟掉`Staging Area`丟掉，拆出來的檔案會直接丟掉

```

// 退回到上一個 commit
$ git reset --hard

// 退回到指定的版號
$ git reset --hard <versionId>

```

## Revert

新增新的 commit 來取消不要的 commit。若在多人協作中想拆掉 commit 可使用這種方法。

```

$ git revert HEAD <commit message>

// revert 不做編輯
$ git revert HEAD --no-edit

```