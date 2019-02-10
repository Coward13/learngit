Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Creating a new branch is quick.
常见的GITHUP命令：
添加库：$ mkdir <file>    $ cd <file>    $pwd  
上传暂存区：git add <file>
提交status ：git commit -m"说明"
查看状态：git status
返回版本：git resset --hard HEAD^   或者（ hard 号码）
查看版本：git log --pretty=oneline
查看所有版本：git reflog
撤销工作区操作：git checkout -- <file>
查看工作区与暂存区区别：git diff HEAD -- <file>
关联远程库：git remote add origin git@github.com:youself/learngit.git
第一次将本地库推送到远程：git push （-u） origin master
从远程克隆到本地库: git clone git@github.com:youself/gitskills.git
创建分支并切换：git checkout -b name 
查看分支：git branch

