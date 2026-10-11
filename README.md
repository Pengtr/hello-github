# hello-github

我的第一个 GitHub 仓库，用来跑通本地 ↔ 远端的完整流程。

## 这条链路是怎么搭起来的

- 认证走 SSH（`git@github.com:Pengtr/hello-github.git`），不用 HTTPS 密码
- 本地仓库位置：`C:\Users\ASUS\source\repos\hello-github`

## 日常三条命令

```bash
git add .
git commit -m "说明这次改了什么"
git push
```

## 笔记

- `git status` 随时看当前状态，不确定就先跑这个
- 第一次推送用的是 `git push -u origin main`，`-u` 把本地 main 和远端 main 绑定，
  之后直接 `git push` 就行
