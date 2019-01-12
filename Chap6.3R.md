# 還原 Commit

## Reset

把目前狀態設定誠某個 commit

### mixed

預設參數，`working directory`不變`Stagin Area`丟掉，拆出來的檔案會放置在`working directory`

```

// 退回到上一個 commit
$ git reset --mixed

// 退回到指定的版號
$ git reset --mixed <versionId>

```
