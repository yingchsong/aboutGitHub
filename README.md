# aboutGitHub

# How to connect local machine to github

Firstly, ssh:
```
cd ~/.ssh

ls

vi id_rsa.pub
```
// ctrl+a,ctrl+c

:q

Secondly, add ssh key in github

Thirdly, Creating a personal access token

Settings -> Developer settings -> Personal access tokens -> Generate new token -> Generate token

copy token and use following command:
```
git remote set-url origin  https://<your_token>@github.com/<USERNAME>/<REPO>.git
```
# clone and push
```
git clone <URL>
```
// see this tutorial:

//https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed-please-use-a-personal

//after update
```
git add <fileName>

git commit -m 'comments'

git push
```

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

readme file format

1. 创建并切换到新的本地分支
首先，在本地创建一个新的分支并切换到该分支。你可以选择使用 git checkout -b 或更现代的 git switch -c 命令（推荐用于 Git 2.23 及以上版本）。

使用 git checkout -b
bash
深色版本
git checkout -b <new-branch-name>
使用 git switch -c (Git 2.23+)
bash
深色版本
git switch -c <new-branch-name>
这将创建一个名为 <new-branch-name> 的新分支，并自动切换到该分支上。
