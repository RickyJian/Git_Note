# GitFlow

Git 分支習慣

[原文網址](https://nvie.com/posts/a-successful-git-branching-model/)

## 分支

主要分支 master、develop、hotfix、release、feature

### Master

長期分支，穩定版本用來放置隨時可上線的版本。只能由其他分支合併過來。

### Develop

長期分支，主要開發分支，所有 Feature 分支皆由此分支分出去

### Hotfix

短期分支，當線上版有問題產生時，會由 Master 分支分出來，當問題修復後會合併進 Master & Develop

### Release

短期分支，上線前的最後測試，只修 bug，當 Develop 夠成熟後會將此分支合進 Release 中，測試完後會將他在合進  Master & Develop

### Feature

短期分支，當功能新增時由 Develop 分出來，開發及測試完畢會合進 Develop 中