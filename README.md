# git常用的命令
## 准备阶段
格式化 `email`和`用户名`
   * `git config --global user.email "you@example.com"`
   * `git config --global user.name "Your Name"` 

初始化仓库：`git init`
> 一般不会用命令来初始化仓库
<!-- 克隆仓库  :`git clone <git地址>` -->
---
## 提交阶段
添加文件到暂存区：
- `git add -A`
- `git add "文件名"`

暂存区的文件提交到仓库:`git commit -m "提交名称"`
查看提交的历史记录：`git log --stat`

工作区回滚：`git chackout 文件名称`
撤销最后一次提交：`git reset HEAD^1`
> HEAD^后没有数字默认是1，也就是最后一次的，数字是几就是倒数第几次的
---
## 分支相关
