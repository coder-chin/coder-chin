## Hi there 👋

- 🔭 I’m currently studying on BJFU.
- 🌱 I’m currently learning Operating System, Algorithm, Front-end engineering, React... 

You can find me:

[标题1](#标题1) 

[标题2](#标题2) 

[标题3](#标题3) 


- [知乎](https://www.zhihu.com/people/whale2002)
- [语雀](https://www.yuque.com/whale2002)
- [掘金](https://juejin.cn/user/598555237295264)
- [BiliBili](https://space.bilibili.com/401694598)


![whale2002's GitHub stats](https://github-readme-stats.vercel.app/api?username=whale2002&show_icons=true)


## 不如反复练习 :memo:
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
