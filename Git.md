常用Git命令;
    name                                    作用
    git config --global user.name 用户名     设置用户签名
    git config --global user.email 邮箱      设置用户签名
    git init                                初始化本地库
    git status                              查看本地库状态
    git add 文件名                           添加到暂存区
    git commit -m "日志信息" 文件名           提交到本地库
    git reflog                              查看历史纪录
    git reset --hard 版本号                  版本穿梭
     
分支的操作:
    name                                    作用
    git branch 分支名                        创建分支
    git branch -v                           查看分支
    git checkout 分支名                      切换分支
    git merge 分支名                         把指定分支合并到当前分支上 
    git remote -v                           查看分支别名    
    git remote add 别名 项目网址              为项目创建别名    git remote add git-demo https://github.com/yutuai/git-demo.git
    git push 项目网址/别名 分支名              将分支推到远程库中 git push git-demo master
    git pull git-项目网址/别名 远程库的分支名   将远程库中某个分支拉回本地库(拉取动作自动提交本地库)   git pull git-demo master
    git clone 项目网址                        将项目clone到本地(不用登陆账号)   git clone git-demo https://github.com/yutuai/git-demo.git 
                      