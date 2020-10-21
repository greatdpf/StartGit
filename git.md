https://github.com/greatdpf/StartGit.git

```
// 提交到缓存区
git add git.md		git add 要提交的文件名
// 提交到本地库
git commit -m "注释" git.md		git commit -m "注释" 要提交的文件名
// 查看状态
git status
// 查看远程地址有没有别名
git remote -v
// 给 https://github.com/greatdpf/StartGit.git 起别名 叫做 startgit 
git remote add startgit https://github.com/greatdpf/StartGit.git
// 将本地的 master 提交到远程仓库的 master。
git push startgit master   git push 别名 要推送的分支
```

