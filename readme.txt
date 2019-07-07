git常用命令

1、 git init			把当前目录变成git可以管理的仓库
2、 git add filename		把修改后的文件添加到暂存区
3、 git status 			查看当前状态是否有未提交或未添加到暂存区的文件
4、 git commit -m "提交描述"	将暂存区的文件提交到本地仓库
5、 git diff 文件名		查看文件修改的内容
6、 git log [--pretty=oneline]	查看历史记录
7、 git reset --hard HEAD^	回退到上一个版本
8、 git reset --hard HEAD~n	回退到前n个版本，n为正整数
9、 git reset --hard 版本号	根据版本号回退
10、git reflog			查看版本号
11、git checkout -- filename	撤销文件在工作区的所有修改
	1) 文件还没add到暂存区，则撤销修改后回到和版本库一模一样的状态
	2) 文件已经add到暂存区后再次修改，则撤销后就回到add暂存区后的状态


