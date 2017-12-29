version 3
git is very good
git is a free software
git is a distributed version control system


git config --global user.name "username"
git config --global user.email "1515@afsf.com"

git init 初始化仓库
git add ..... 添加文件到暂存区
git commit -m "说明" 提交文件到仓库
git log 查看日志
git log --pretty=oneline 查看日志
git reflog 历史记录
git reset --hard (version) 版本回退
git reset --hard HEAD 回退当前版本，用于撤销提交到暂存区的文件
git checkout -- file 撤销工作区的修改
git status 查看当前仓库状态

git remote add origin https://github.com/Binssss/mygit.git 上传本地仓库代码到github 远程仓库
git push -u origin master 上传代码