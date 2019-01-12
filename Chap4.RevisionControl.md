# 版本控管

版本控管流程

![Status](/images/Status.png)

```

// 檢查檔案版控狀態
$ git status

```

## Working Directory(工作區)

未被 Git 版控的檔案

```

// 單檔加入 Staging Area
$ git add <fileName>

// 將所有副檔名加入 Staging Area
$ git add <.html>

// 全檔加入 Staging Area
$ git add --all

```

## Staging Area(暫存區)

Git 版控的暫存檔案

```

// 完成版控，將檔案寫入到 Repository
$ git commit -m '<commit message>'

```

## Repository(儲存區)

Git 完成版控所放置的地方