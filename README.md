# TickJava
Tick java project.

### 项目说明
```dtd
java 基础项目案例。
```

### github 项目管理和开发
```dtd
1）新建github账户
2）安装git
3）创建本地 ssh key（一台电脑仅需创建一次）；并查找到 id_rsa.pub文件；一般在c盘 C:\Users\DELL\.ssh
4）github登录个人账户之后，在setting中设置ssh key。
5）从远程clone仓库到本地
git clone ssh.xxxxxx
```

### 代码提交说明
```dtd
1）git pull
拉取代码。目的是更新远程分支的变更到本地，避免在同一条分支开发的成员有提交，导致本地提交代码有冲突。

2）git status
查看本地代码变更情况。

3）git add "项目代码"
git add .
表示提交所有的变更文件
git add demo1/
表示仅提交demo1文件夹下的变更
git add demo.java
表示仅提交demo.java文件的变更

4）git commit -m ""
提交变更内容到本地仓库，并添加对应的注释。
注释规范：
功能类 - [feature] xxxx
bug修复类 - [bug] xxxx

5）git push
提交本地仓库代码到远程仓库
```

```dtd
常见的git操作命令行
本地分支切换
git checkout xxx 
远程分支切换到本地，并创建本地分支
git checkout -b 本地分支 origin/远程分支

当前分支合并其他分支，比如当前在test分支合并dev分支
git merge dev

其它需要用到的命令行，使用百度进行搜索
```
