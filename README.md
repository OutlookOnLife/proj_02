# proj_02
这是第二个测试的仓库（Github上仓库的名字 和 本地项目的名字 ，不一定非得保持一致）。


# 2023.03.05
这个readme.md文件是从github的proj_02仓库中自动创建的。

出现这个问题是因为github中的README.md文件不在本地代码目录中，
可以通过  git pull --rebase origin master命令  进行代码合并。

# 2023.03.06
1.master主分支在创建的时候是没有代码的

每个功能分支，开发一个功能模块，最终合并到主分支上


2.
下面代码是测试  提交测试js文件，待会儿准备把这个远端的test分支给删除
console.log('这个是一个新的分支，测试分支')
console.log('先将该ceshi分支推送到远端仓库中')
console.log('之后再把该分支删除')
console.log('该文件就在该分支上')


先利用 git push origin --delete 远端分支名称 的命令：删除远端仓库分支名称

再用 git branch -d 本地分支名称 删除本地仓库中该分支的代码。
git branch -D 本地分支名称 命令是彻底删除该分支的代码。

3.重点：将本地的分支删除：我直接把它合并到主分支不就完了

4.属于 遇到冲突时的分支合并 的情况

  对master分支的 README.md文件 进行了修改（都得到提交那步）
  对ceshi 分支的 README.md文件 进行了修改（都得到提交那步）