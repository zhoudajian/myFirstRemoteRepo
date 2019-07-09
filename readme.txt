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
11、git checkout -- filename	撤销文件在工作区的所有修改/恢复删除(rm)但未commit的文件
	1) 文件还没add到暂存区，则撤销修改后回到和版本库一模一样的状态
	2) 文件已经add到暂存区后再次修改，则撤销后就回到add暂存区后的状态
12、rm file			删除文件
13、ssh-keygen -t -rsc -C "youremail@example.com"	生成ssh key
14、git remote add origin RemoteAddress			关联远程仓库
	我的地址：https://github.com/zhoudajian/myFirstRemoteRepo.git
15、git clone RemoteAddress	从远程克隆一个本地版本库
16、git branch			查看分支
17、git branch 分支名		创建分支
18、git checkout 分支1		从当前分支切换到分支1，
			      * 切换后，工作区文件内容变为分支1最后一次提交的内容。
			      * 当前分支未提交的文件和内容也跟着切换到分支1中；
			      * 若某个文件内容被修改后与分支1中文件有冲突则报错；
			      * 且在哪个分支下提交就变为哪个分支的内容，不会再保留到另一分支。		
19、git checkout -b branchname	创建并切换分支（相当于17和18的结合）
20、git push -u origin branchname	将本地branchname分支更新的代码推送到远程branchname分支(第一次需要-u, 以后不需要)，
21、git pull origin 分支名	从远程分支拉取更新
22、git merge dev		在当前的分支上合并dev分支
23、pwd				显示当前目录的路径
24、mkdir			创建文件夹
25、touch			创建文件
26、cat				查看文件内容
26、git stash			把当前的工作隐藏起来，等以后恢复现场后继续工作（用于bug修复）
27、git stash list		查看所有被隐藏的文件列表
28、git stash apply		恢复被隐藏的文件，但是内容不删除
29、git stash drop		删除文件
30、git stash pop		恢复文件的同时也删除文件
31、git remote			查看远程库的信息
32、git remote -v		查看远程库的详细信息
