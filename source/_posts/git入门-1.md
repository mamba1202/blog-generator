---
title: git入门
date: 2018-12-30 21:23:02
tags:
---
介绍 git init,git add,git commit的用法
1. git init (初始化本地仓库.git)
a: 当你本地创建了一个工作目录，你可以进入这个目录，使用'git init'命令进行初始化
b: 例：我们创建一个目录作为项目目录：mkdir git-demo 
c: 进入目录 cd git-demo
d: git init,这句命令会在git-demo里创建一个.git目录

{% asset_img QQ截图01.jpg This is an QQ截图01 image %}
2. git add 将文件添加到【暂存区】
a: 你可以一个一个的add
   git add index.html
b: 也可以一次性add
   git add . 意思是把当前目录中（.表示当前目录）里面的变动都加到【暂存区】
{% asset_img QQ截图02.jpg This is an QQ截图02 image %}
3. git commit 用来正式提交变动,提交至.git仓库
git commit index.html -m '添加index.html
{% asset_img QQ截图03.jpg This is an QQ截图03 image %}

