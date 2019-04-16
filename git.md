# 分支处理
1. 创建分支
	> git checkout -b dev
2. 创建远程分支
	> git push origin dev:dev
3. 删除分支
	> git branch -d dev
4. 删除远程分支
	> git push origin --delete dev
5. 合并分支
	> git merge dev
6. 本地创建并与远程分支关联
	> git checkout -b dev origin/dev
