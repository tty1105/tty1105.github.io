---
title: 'How to backup your script to github'
date: 2025-11-28
permalink: /posts/2025/11/backup/
tags:
  - codes
---

在这里我记录下如何快速将你的代码备份到github。<br>


非常粗糙，还要学习（叠甲）。<br>
首先进入到需要备份的目录下，在命令行中输入：
```
git init
```
在你的github里新建一个repository，不要添加README文件（根据deepseek的指示）。新建完之后将你本地的仓库跟远程的仓库关联起来，在命令行中继续输入：
```
git remote add origin https://github.com/你的用户名/你的仓库名.git
```
这一步有可能会报错，让你做一步```git config --global --add safe.directory``` 什么什么的，照做就是，然后重新运行上面的命令。之后需要在你的目录里新建一个```.gitignore```文件，由于我们只备份自己写的代码，不备份数据，添加这个文件可以在备份的时候忽略掉一些我们不想备份的东西。在这个文件里写：
```
# ignore everything
*
# but not directory
!*/
# allow scripts
!*.py
!*.ipynb
# ignore the software directory
software/*
```
井号开头的是注释。在这里我还忽略了```software```目录下的所有文件，这里是我下载过的其它的库之类的，就不用备份了。做完之后就可以：
```
git add .
git commit -m "Initial backup"
```
第一步```git add .```可能会比较慢，后面在备份的时候会快很多。然后就可以：
```
git branch -M main
git push -u origin main
```
这样就完成第一次备份了！在```git push```时会输入一个用户名和密码，用户名就是你的github用户名，而密码需要自己生成，而不是你的登录密码。在你github里点头像，进入Settings，在左下角找到Developer settings，选择Personal access tokens里的Tokens (classic)，然后generate new token。随便写一个名字，然后Repository access我选的是All repositories，下面的Permissions在Add permissions里把全部都点上，然后所有的权限能改的全部改成Read and write（应该是不用改这么多的，但是我懒得仔细看了），之后生成token，注意此时要把这个token复制下来保存起来，之后就不会再显示了。<br>
做完这一步之后```git push```可能还会报错，说```remode: Invalid access to repository not granted```。这个时候在你的仓库里选Settings，在左侧选择Actions里的General，在下面的Workflow permissions里选上Read and write permissions。做完这一步之后我再```git push -u origin main```就成功了，需要等一会儿就可以按照原有的目录结构备份所有的代码。
