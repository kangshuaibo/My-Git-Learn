# My-Git-Learn
首先github上建立仓库clone到本地 编辑后push上去
part one最基本的git命令
git add .             //全部添加到注意有个点
git commit -m "note"  //提交 后面双引号内为本次的注释，方便回退时查看要回退的版本
git push              //同步到github仓库
//注意：若修改了github上的内容需要pull回来

part two回退
git reflog   //查看要回退的版本 注释起作用








git reset --hard commit-id  //回滚到commit-id，讲commit-id之后提交的commit都去除
git reset --hard HEAD~3 //将最近3次的提交回滚
