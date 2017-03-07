# rust
**第一次使用git 命令小结**
1.设置用户名
git config --global user.name 'photo520'
2.设置邮箱
git config --global user.name 'alexa456@163.com'
接着初始化仓库（要做项目目录里面初始化）
git init
#想仓库提交文件
touch a1.php (创建一个文件) 
git status 
git add a1.php (添加指定文件到暂存区)
git commit -m 'a1.php' (从暂存区提交到仓库)
#修改仓库文件
vi a1.php
#修改之后的文件使用 git status 查看是否修改
git add a1.php(添加指定文件到暂存区)
git commit -m '我有修改了a1.php文件了，提交到仓库'


#从仓库删除文件
git rm a1.php
git commit -m '第一次删除仓库的文件'

#将本地仓库提交到远程仓库
#首先将 远程代码clone到本地
===================================
mkdir 文件名 【创建文件夹】
rm -rf a1.php

初始化后，下载远程文件：
git clone https://github.com/potato520/rust.git

git add xx
git commit -m '介绍'
git push



=============查看配置 git config --list
