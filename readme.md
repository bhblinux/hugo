
   1. 查看当前git状态
      	
git remote add hugo https://github.com/bhblinux/hugo.git
git push hugo master:work
1. git push
git push -u origin/remote_branch
git push hugo work:work
1. 远程分支问题
- 查看远程分支
	git branch -a 
- 查看本地分支
	git branch
- 创建分支
	git branch test
- 把分支推送远程分支
	git push origin test
- 切换分支
	git branch test
- 删除本地分支
	git brnch -d test
- 删除远程分支
	git push origin --delete test







;;设置打开文件字符集
M-x revert-buffer-with-coding-system utf-8
;;设置保存的时候指定字符集
M-x set-buffer-file-coding-system


