# Git 常用指令速查表

* add test.txt
  更新test.txt到暂存区
  add *
  更新所有文件到暂存区
  
* branch
  查看分支
  branch dev
  创建dev分支
  branch -d dev
  删除dev分支
  
* checkout
  检出
  checkout -- test.txt
  从版本库检出test.txt文件到工作区
  checkout dev
  切换到dev分支
  checkout -b dev
  创建dev分支并切换到dev分支
  
* commit -m "<message>"
  提交更新
  
* init
  创建仓库
  
* log
  查看提交日志
  log --pretty=oneline
  以一行显示
  log --graph
  显示分支
  log --abbrev-commit
  显示版本号前几位
  log --graph --pretty=oneline --abbrev-commit
  组合使用风味更佳
  
* merge
  合并
  merge dev
  合并dev分支到当前分支
  
* reflog
  查看操作日志
  
* reset
  回退
  reset --hard HEAD^
  回退到前一个版本并丢弃更改
  reset --hard HEAD~2
  回退到前两个版本并丢弃更改
  reset --hard 7169f73
  回退到版本号为 7169f73 的版本
  
* status
  查看状态
  
* tag
  查看所有标签
  