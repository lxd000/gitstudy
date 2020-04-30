# Git 学习资料整理笔记
## 1 课程介绍
## 2 Git基础命令
## 创建版本库

- mkdir gitstudy "创建一个名叫gitstudy的空目录"
- cd gitstudy "把gitstudy设置为当前目录"
- pwd "查看当前目录"

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
- git reset <版本号> "版本的作用区域回到未提交之前的区域"
- git reset --soft <版本号> "把需要的版本加载到暂存区"
- git reset --hard HEAD^^ "移动版本号"

## git rm/mv
- git rm <file/menu>
- git rm --cached <file/menu> "删除指定文件的跟踪/删除暂存区里的文件"
- git mv <文件原来位置> <文件或目录的新位置>
- git mv <文件的旧名字> <文件的新名字>

## git remote
- git remote add <自定义名称> <源路径>
- git remote remove <自定义名称> "删除自定义名称"
- git remote show "展示之前添加的自定义名称"
- git remote -v "显示所有的git服务器地址"
- git remote rename <旧名> <新名>

## git push
- git push <remote name> <master 版本分支>
- git push -u <remote name> <master 版本分支>ss
- git push --all "推送所有分支到服务器"

## git branch
- git branch <new name>
- git checkout <branch name>
- git checkout -b <branch name> 等同于 "git branch <new name>" + "git checkout <branch name>"



