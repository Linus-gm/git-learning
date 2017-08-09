开始学习git版本控制管理
1.vim在normal模式下使用:wq命令保存退出
2.git add可提交多个文件到暂存区
3.修改的内容需要提交到缓存区才可以commit
4.没有提交到缓存区的就在工作区
5.git checkout -- <file>放弃工作区未暂存的修改
6.git reset HEAD <file>放弃暂存区的修改
7.git rm <file>可提交删除操作到暂存区，然后git commit确定删除版本库中的文件
8.git push origin master把本地master推送至远程
9.关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
