## git Command

####　git --version

#### git status 查看当前工作区的状态

#### git add <文件名> 将工作区的文件加入暂存区

#### git commit -m "输入一些备注信息，比如说是该版本的介绍或者是于旧版本的区别"  将暂存区的文件放入远程库

#### git remote add origin <GitHub上的仓库的HTTP的链接> 连接远程库

#### git remote -v 查看连接的是哪一个远程的仓库

#### git branch 查看分支

#### git diff <文件名> 查看文件与上一个版本的区别

#### git log 查看上传的日志信息，会有每次提交的版本号，均是十六进制

#### git log --pretty=oneline 查看日志信息，不过每个版本信息会变成简短的一行

#### git reset --hard HEAD^ 版本回溯，HEAD相当于一个指针，HEAD^相当于指向下一个节点（就是上一个版本）

#### git reflog  查看版本回溯的信息，在你后悔删除一个版本后，可以查看删除版本号，为reset做准备

#### git reset --hard <版本号的前几位，但不要太短> 