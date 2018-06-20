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