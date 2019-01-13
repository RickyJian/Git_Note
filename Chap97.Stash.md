# Stash

暫存現在檔案狀態，但只限於檔案被版控時才能暫存

## 新增

```

$ git stash

```

## 檢視

```

$ git stash list

```

## 回復

### pop

回復後會將 stash 刪除

```

$ git stash pop stash@{<stash id>}

```

### apply

回復後不會將 stash 刪除

```

$ git stash apply stash@{<stash id>}

```

## 刪除

```

$ git stash drop stash@{<stash id>}

```