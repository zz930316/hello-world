# hello-world
常用的git命令：
git diff 查看当前文件更改了哪些内容
git pull origin master : 更新本地代码
git branch xxx : 新建分支xxx
git checkout xxx : 切换到xxx分支
git push origin xxx : 将分支xxx的代码提交到远程仓库
git status : 查看当前有变化的文件
git add . : 将本地所有文件加入到索引列表(以后只要修改或者删除这些文件都会有记录)
git commit -m "此次修改的内容" : 将修改的内容提交到本地仓库
大概流程：获取远程代码(git pull origin master) -> 修改本地代码 -> 提交到本地仓库(git commit) -> 提交到远程仓库(git push) 
git还有很多命令，但工作中最常用到的只有这些命令，如果对于git内部运行机制或者命令感兴趣的话，可以看看Pro Git: http://git.oschina.net/progit/ 