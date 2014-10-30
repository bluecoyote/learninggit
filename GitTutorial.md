#### Git教程命令练习

> 练习内容来自廖雪峰的博客
> http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

git init

git add filename

git commit -m "your comments"

git status 

...

after adding remote git repo

...

向Github仓库推送流程：

> - git add somefile         //添加文件
> - git commit -m "comments" //提交
> - git push -u origin master//推送到Github仓库


		git checkout -b dev 
 
 与
 
		git branch dev//创建分支
		git checkout dev//切换分支
		
等价

平时开发中多用git分支，master分支用来发布稳定版，dev分支用来进行开发；开发中每人都有自己的分支，时不时往dev分支合并就好了。

##### 参与开源
- 首先fork开源项目
- git clone 到本地
- 提交修改
- 发送 pull request 给原项目作者