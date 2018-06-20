### tree

需要安装

输出目录结构

指定层级输出

```powershell 
# -C 着色
# -L 指定层级
tree -C -L 3
```


### alias

最初纠结在 git commit -m 'default commit ' 中的单引号如何与 alias 定义中的单引号相融，google 上也有解决方案，但是太麻烦了，操作一定要简洁，所以 commit 这个单引号，改双引号就好了。

``` powershell
# 为复杂操作起别名
alias tgmt = 'git commit -m "default commit"'

```

但还要 git add .  和 git push , 懒人绝不多做事，重新定义别名，合并多个命令

```powershell
alias tgmt = 'git add . && git commit -m "default comment" && git push origin master'

```

之后同步资料，tgmt 就ok了，完美。