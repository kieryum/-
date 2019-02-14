
##### git init
##### git add README.md
##### git commit -m "first commit"
##### git remote add origin https://github.com/BrentHuang/MyRepo.git
##### git push -u origin master


##### 在本地新建一个分支： git branch Branch1
##### 切换到你的新分支: git checkout Branch1
##### 将新分支发布在github上： git push origin Branch1
##### 在本地删除一个分支： git branch -d Branch1 （删除已合并的分支）
##### 强制删除分支：git branch -D crazy-idea
##### 在github远程端删除一个分支： git push origin :Branch1   (分支名前的冒号代表删除)

##### 直接使用git pull和git push的设置

##### git branch --set-upstream-to=origin/master master 
##### git branch --set-upstream-to=origin/ThirdParty ThirdParty
##### git config --global push.default matching

##### 合并分支：git merge experimental （在主分支上执行：目前不是太明确具体用法 个人理解是在主分支上合并到主分支上的其他分支）
##### 查看冲突：git diff
##### 查看日志：gitk 

##### 撤销合并的分支：git reset --hard HEAD
##### 撤销以合并并且提交了的分支：git reset --hard ORIG_HEAD
