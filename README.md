# git
git 学习踩坑及常用命令行

## 学习教程

* [git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## 常用命令行

* git init

* git clone -b develop https://username:password@remote

* git checkout -b xxx (创建并切到本地xxx分支)   

* git checkout xxx (切换分支)

* git merge bxx (当前所在分支合并bxx分支的修改)

* git branch -d xxx  (删除本地xxx分支, 当前所在分支是xxx以外的分支)

* git clean -df  git reset --hard (还原本地目录)
    
    

## 常用命令图片

![Alt text](https://github.com/UC10D/git/blob/master/image/Command%20Line.jpg)

## ssh相关

* [Git 【基于SSH协议clone GitHub远端仓库到本地】](http://blog.csdn.net/felicity294250051/article/details/53606158)
* [使用GitLab，Mac下如何生成SSH Key](https://www.jianshu.com/p/46aaccc71ce8)
* [Git - 生成ssh key步骤以及如何clone所有的远程分支](https://www.cnblogs.com/gongyuhonglou/p/6922721.html)

## soft

* SourceTree
* TortoiseGit 查看单个文件提交log

## ps

* 忽略文件, 如果在提交工作空间, 需要先删除
* git config core.ignorecase false 设置大小写敏感
