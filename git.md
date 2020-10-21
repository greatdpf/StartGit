https://github.com/greatdpf/StartGit.git

```
// 初始化本地库
git init
// 提交到缓存区
git add git.md		git add 要提交的文件名
// 提交到本地库
git commit -m "注释" git.md		git commit -m "注释" 要提交的文件名
// 查看状态
git status
// 查看日志   可能会出现分页（下一页：空格，上一页：b，结束：q，下一条：enter）
git log 
git log --petty=oneline
git log --oneline
// 查看回到之前历史版本需要多少步
git reflog
// 指针回退，工作区，缓存区，本地库都会重新回退
git reset --hard 索引号
// 指针回退，缓存区，本地库都会重新回退;工作区不变
git reset --mixed 索引号
// 指针回退，本地库都会重新回退;缓存区，工作区不变
git reset --soft 索引号
// 将工作区的文件和缓存区的文件进行比较
git diff 文件名
// 比较缓存区和本地库的文件区别
git diff 索引 文件名
// 查看分支
git branch -v
// 创建分支
git branch 分支名
// 切换分支
git checkout 分支名
// 

// 查看远程地址有没有别名
git remote -v
// 给 https://github.com/greatdpf/StartGit.git 起别名 叫做 startgit 
git remote add startgit https://github.com/greatdpf/StartGit.git
// 将本地的 master 提交到远程仓库的 master。
git push startgit master   git push 别名 要推送的分支
```

