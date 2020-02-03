# 基本指令

```
git config --global user.name "Dhgalaw"
git config --global user.email "xxx"
```



创建工程：

```
mkdir project_git
```

进入工程：

```
cd project_git
cd ./file
```

初始化项目：

```
git init
```

查看状态：

```
git status
```

添加到缓存区：

```
git add filename1
git add filename1 f2 f3
git add . 
```

提交至版本库：

```
git commit -m "注释"
```





# 版本回退

查看版本：

```
git log
git log --pretty=oneline
```

回退操作：

```
git reset --hard 提交编号
```

回退再回到未来：

```
git reflog
git reset --hard 编号
```





# git与github

创建本地项目文件夹

```
mkdir projectfile
```

进入该文件夹

```
cd ./projectfile
```

克隆线上仓库到本地

```
git clone https地址
```

本地仓库操作

```
git add file
git commit -g "注释"
```

本地提交到线上仓库

```
git push
```





拉取线上仓库

```
git pull
```



每天工作之前先pull，下班之前要push



# git分支

查看分支：

```
git branch
```

创建分支：

```
git branch 分支名
```

切换分支： 

```
git checkout 分支名
```

删除分支：

```
git branch -d 分支名
```

合并分支：

```
git merge 被合并的分支名
```





# 小工具

### git小工具

#### 1.图形管理工具

github for desktop

source tree

tortoisegit  针对于svn