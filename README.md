# My-Git-Learn
首先github上建立仓库clone到本地 编辑后push上去
part one最基本的git命令
git add .             //全部添加到注意有个点
git commit -m "note"  //提交 后面双引号内为本次的注释，方便回退时查看要回退的版本
git push              //同步到github仓库
//注意：若修改了github上的内容需要pull回来

part two回退版本操作
git reflog   //查看要回退的版本(缩略) 注释起作用
git log      //命令查看所有的历史版本（全），获取某个历史版本的id
![Image text](https://raw.githubusercontent.com/kangshuaibo/My-Git-Learn/master/git-readme-img/屏幕快照%202018-10-13%20上午12.53.36.png)

git reset --hard 139dcfaa558e3276b30b6b2e5cbbb9c00bbdca96//回滚到某一版本
git reset --hard HEAD~3 //将最近3次的提交回滚
git push -f -u origin master //把修改推到远程服务器









