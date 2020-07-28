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


### 在服务器上搭建git
https://git-scm.com/book/zh/v2/%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84-Git-%E5%9C%A8%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E6%90%AD%E5%BB%BA-Git#_getting_git_on_a_server
https、git、ssh协议方式的利弊，以及如何配置