Git is a disversion control system.
Git is free software.
$ git add readme.txt----"将文件添加到本地git仓库中，前提是你要在c盘用户的learngit目录下（被定义为本地仓库）"
$ git commit -m"write a readme file"---“告诉git把文件提交到仓库中-m是提示语句”
git status--可以让我们始可掌握仓库当前状态（修改未提交、没有要提交或被修改的，将要被提交的），红色标记的是修改的文件名称，下面的diff会用到
git diff---查看具体修改了哪些内容
git log命令显示从最近到最远的提交日志(如果嫌显示的数据太杂可以加上  --pretty=oneline(head表示当前版本))
git reset --hard HEAD^---将当前版本回退到上一个版本（HEAD^^则表示上上版本）
cat 文件名---查看指定文件的内容
git reset 还可以追会最先的版本，当你回溯上一版本是，当前版本如果是最新那么之后使用git log查看会得不到这一版本的版本号（开头的一串数字）这不是代表他消失了，而是说最新的被隐藏起来了，往上找到它的版本号（之前的回溯上一版本那边会有它的版本号（git log那边），记下来）
使用  git reset --hard 最新版本号（前5个数字一般就够了）   即可回到最新状态
git reflog  --用来显示记录你的每一次命令---也能找到最新的的版本号（moving to 版本号）
git checkout --文件名  把该文件在工作区的修改全部撤销




















