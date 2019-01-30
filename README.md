# git入门学习
# Git是一款源代码管理工具（版本控制工具）
# 1.git安装
# 2.第一次提交在gethub上创建仓库
    2.1 首先初始化.git---执行git init
    2.2 简历忽略文件
        忽略文件.gitignore设置忽略文件,不会被提交到仓库中去
        /.idea
    2.3 上传到本地仓库.git中
        git add ./
        git commit -m “说明”

    2.4 git  status 查看当前代码有没有被当到仓库中
    2.5 查看提交日志
        `git log` : 查看所有日志
        `git log --oneline` : 一行显示一个日志, 更精简

# 3.上传到远端github
    git push https://github.com/wjb-xqx/git-study.git master

# 4.再次提交功能--创建分支
    1. 创建分支
   `git branch 分支名`
    2. 查看当前仓库的所有分支
    `git branch`
    3. 切换分支
    `git checkout 分支名`
    4. 在分支中提交代码

    5. 切换到主分支，合并分支(将指定分支合并到当前分支)
    `git merge 分支名`

    6.上传到github服务器上
    git push  https://github.com/wjb-xqx/git-study.git master

    小技巧:
    `git checkout -b 分支名` : 创建分支并切换到新创建的分支



# 拿到github数据
第一次拿到数据用clone
后面都用pull拿到数据
1.初始化一个仓库git init
2.git pull 【地址】 master即可


多人开发(小明与小红)
先提交到本地，再push到远程服务器