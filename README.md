# Git 学习资料整理笔记
## 1 课程介绍
## 2 Git基础命令

- 'git init' 初始化Git仓库

工作区 -> 暂存区
- 'git add <文件名或目录名>' 提交工作区文件到暂存区

工作区 -> 暂存区 -> 本地版本库
- 'git commit -m "为什么要提交的注释"' 提交到本地版本库

- 'git status' 查看工作区状态

- 'git diff <文件名/目录名称> [--cached]' 版本内容对比

## git log 查看版本

- git log
- git log <-number>
- git log -p <-number>
- git log --stat "以缩略行的形式显示版本之间的差异"
- git log --oneline "以一行的形式显示版本之间的差异"
- gitk "以GUI界面的形式显示版本之间的差异"

## git reset

- git reset --hard <版本号> "强硬的把工作区全部覆盖"
- git reset <版本号> ""
- git reset --soft <版本号> ""
- git reset --hard HEAD^ "移动版本号"

