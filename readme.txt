Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
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
