# Learn Git

《十万伏特 学习笔记》- Git 学习

## Git 简介

Git 是目前世界上最先进的分布式版本管理系统

## 安装和配置

安装
```bash
sudo apt-get install git
```

设置
```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```

由于 git 是分布式版本控制系统，每个机器都必须自报家门。
`global` 表示这台机器上所有 Git 仓库都使用这个配置

## 创建版本库

1. 初始化 Git 仓库 `git init`
2. 添加文件到 Git 仓库
    - 第一步： `git add <file>`
    - 第二步： `git commit`

`git commit` 说明: commit 提交，就像游戏中的存档，可以保存多个存档，并且每个存档可以加上不同的说明。
`git commit -m '说明文字，表示更改添加的内容'`
