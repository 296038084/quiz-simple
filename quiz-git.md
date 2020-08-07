# Git 的使用

## Q1

Git 是一个广泛使用的版本管理工具，适合团队开发。  
如果你用过 Git，那么请回忆一下，  
我们在确认开发需求之后，从写代码到提交进团队的代码仓库。  
这个过程中大概会用到哪几条命令？

请直接在这里作答。

答：
git config --global user.name
git config --global user.email
git init
git add
git commit -m "initial commit"
git remote add origin
git push origin master

git操作：Git Bash Here
Git Clone
TortoiseGit->Switch/Checkout
Git Commit
TortoiseGit->Pull


## Q2

你知道和用过哪些 Git 的方法论和技巧

答：
在每次获取文件之前要先进行文件更新。
可以使用 %>git add -i 来启动交互式添加器分开上传文件。
