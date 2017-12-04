本地仓库
{

	初始化仓库 git init

	添加文件 git add<file>

	更新提交 git commit -m ""

	仓库状态 git status
	
	查看修改内容 git diff

	查看提交日志 git log

	回退版本 git reset -- hard HEAD^

	每次提交命令 git reflog

	丢弃工作区修改 git checkout -- file

	丢弃暂存区修改 git reset HEAD file

	删除工作区文件 rm <file>

	删除版本库文件 git rm <file>
}

远程仓库
{
	创建SSH Key ssh-keygen -t rsa -C "1051295114@qq.com"
	
	关联远程库 git remote add origin @url

	推送本地库到远程 git push -u origin master
	
	-u 为分支关联，以后更新可以不用
}