# gitdemo
练习git命令

### clone 
git clone <url>
```
git clone https://github.com/libgit2/libgit2
git clone https://github.com/libgit2/libgit2 mylibgit //指定本地仓库的名字
```
### status
查看那些文件处于什么状态
```
git status
git status -s
git status --short
```

### add
```
git add README
```

### diff
查看暂未暂存的文件更新了那些部分
```
git diff
git diff --staged //查看已暂存的文件与最后一次提交的文件差异
git diff --cached //查看已暂存的变化
```
### rm
移除文件,先从已跟踪文件中移除，然后提交
```
git rm
```
### mv
文件改名
```
git mv file_from file_to
```
运行`git mv`相当于运行三条命令
```
mv README.md README
git rm README.md
git add README
```

### 查看提交记录
```
git log
git log -p //每次提交所引入的差异
git log -2 //限制每次输出日志的条数为2条
git log --stat //选项在每次提交的下面列出所有被修改过的文件、有多少文件被修改了以及被修改过的文件的哪些行被移除或是添加了
```

### commit
```
git commit --amend //重新提交
git commit -m 'initial commit' //提交
```
### reset
取消暂存的文件
```
git reset HEAD <file>
git reset HEAD file.md
```
### checkout
撤销对文件的修改
```
git checkout -- file.md
```

### 在服务器上搭建git
https://git-scm.com/book/zh/v2/%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84-Git-%E5%9C%A8%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E6%90%AD%E5%BB%BA-Git#_getting_git_on_a_server
https、git、ssh协议方式的利弊，以及如何配置