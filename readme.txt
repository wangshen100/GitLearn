Git is a disversion control system.
Git is free software.
$ git add readme.txt----"将文件添加到本地git仓库中，前提是你要在c盘用户的learngit目录下（被定义为本地仓库）"
$ git commit -m"write a readme file"---“告诉git把文件提交到仓库中-m是提示语句”
git status--可以让我们始可掌握仓库当前状态（修改未提交、没有要提交或被修改的，将要被提交的），红色标记的是修改的文件名称，下面的diff会用到
git diff---查看具体修改了哪些内容
git