## git 使用
==`cd /d/git-base` 进入git仓库==
`ls /d/` 查看d盘
`git remote -v` 进入任意目录后看当前是否为本地仓库
git ls-files 查看所有文件
1. 本地推送github
	- 文件放入仓库---d/git-base
		- ==`cp /d/笔记/xxx.md .` 单文件复制==
		- `cp -r /d/笔记/某文件夹 .` 整个文件夹
	- 用git加入
		- `git status` 查看那些文件是新加的为红色
		- ==`git add .` 加入所有==
			- `git add xxx.md`
			- `git add 某文件夹/`
		- `git status` 确认，文件变绿色
	- 提交并推送
		- ==`git commit -m "备注信息"` 提交==
		- ==`git push` 推送==
2. github推送本地
	- ==cd /d/git-base==
	- ==git pull==
3. 删除文件 `cd rm 文件名.md`和`git rm -r 文件夹名`
4. 创建文件 `nvim xxx.md`
5. 关闭 `exit`
