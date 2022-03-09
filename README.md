<!-- ### Hi there 👋 -->
<!-- ![coder-chin's GitHub stats](https://github-readme-stats.vercel.app/api?username=coder-chin&show_icons=true) -->

## 不如反复练习
### 本地分支先开好然后推送到远程
```shell
git checkout -b feature-branch                   
git push origin feature-branch:feature-branch
```

### 将本地分支和远程关联
```shell
git branch --set-upstream-to=origin/develop develop
```

### 删除分支
```shell
git branch -D localBranchName
git push origin --delete remoteBranchName
```

### Fork 后与原仓库同步
```shell
git remote -v
git remote add upstream git@github.com:TuSimple/naive-ui.git
git fetch upstream
git checkout main
git merge upstream/main
git push
```
