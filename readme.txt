Git is a distributed version control system.
Git is free software.
创建分支：git branch <name>
查看分支：git branch
新加内容：
查看远程库信息，使用git remote -v；
本地新建的分支如果不推送到远程，对其他人就是不可见的；
从本地推送分支，使用git push origin branch-name，如果推送失败，先用git pull抓取远程的新提交；