* git --version 查看git版本
* git init  初始话一个git文件
* git add . 从本地区放到暂存区
* git commit 从暂存区放到远程仓库
* git status 查看当前项目有哪些改动
* git log 查看所有提交记录
* git log --author='xxx' 查看具体某人提交的代码
* git config --global user.name 'xxx' 配置git用户名
* git config --global user.email 'xxx' 配置git用户邮箱
* git config --global --list 配置的信息
* git rm xxx 删除文件
* git mv xxx yyy 重命名文件
* git log --pretty=onelime xxx 查看文件变化
* git show xxxxxx  查看具体提交的内容
* git log -p xxx 查看具体修改的内容
* git diff 查看不同(改动内容不多的情况下)
* git checkout -- xxx 把未提交的文件恢复到上次提交状态
* git reset HEAD xxx 从暂存区撤销
* git reset --hard HEAD^ 整个代码版本回退(一个^代表一个版本)
* git reset --hard xxxxxx 回退到具体某个版本
* git push origin main 推送远程仓库
* git tag xxx 创建标签 默认是加到最新一次的commit上面
* git tag xxx xxxxxx 给某个版本加标签
* git tag -d xx 删除某个标签
* git push origin xx(v1.0) 把标签推送到远程仓库
* git branch xx 创建分支
* git branch 查看分支
* git checkout xx 切换分支
* git branch -d xx 删除分支，不能删除当前所在分支
* git checkout -b xx 创建并切换分支