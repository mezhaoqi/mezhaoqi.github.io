---
title: git
date: 2023-12-28 11:11:10
tags:
---

### 1、git常用命令
``` bash
# 配置用户名
git config --global user.name "gitee注册的用户名"
# 配置邮箱
git config --global user.email gitee配置的邮箱
# 查看配置
git config --list
# 初始化仓库
git init
# 添加到暂存区
git add .
# 记录到版本库
git commit -m"信息"
# 简略信息
git log --oneline
# 完整信息，如果出现无法退出，可以按 q
git log
# 切换到指定版本
git reset --hard 版本号
# 查看完整历史（版本切换之后git log可能会出现无法查看的情况）
git reflog
# 查看文件状态
git status
```
### 2、`.gitignore` 部分语法
``` bash
# 这里演示的部分语法
# #之后的内容是注释 会被Git忽略
# 忽略 info.txt 文件
info.txt
# 忽略 .vscode/ 目录下所有的文件
.vscode
# 忽略目录下所有.md结尾的文件
*.md
# 会忽略 doc/目录下扩展名为txt的文件
doc/*.txt
```

### 3、分支
``` bash
# 创建分支
git branch 新分支名
# 查看分支
git branch
# 切换分支
git checkout 分支名
# 重命名分支 ，如果默认是master，可以通过这个命令改为main
git branch -m 老分支 新分支
```

### 4、合并分支
``` bash
# 将指定分支合并到当前分支
git merge 分支名
# 删除已合并的分支
git branch -d 分支名

# 这些是目前学习的分支相关命令
# 创建分支
git branch 新分支名
# 切换分支
git checkout 分支名
# 查看分支
git branch
# 切换分支
git checkout 分支名
# 重命名分支 ，如果默认是master，可以通过这个命令改为main
git branch -m 老分支 新分支
```