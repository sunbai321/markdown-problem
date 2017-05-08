# GitHub问题集2
## 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
新的仓库 重要的仓库  新的代码片段  新的组织

## 如何能将仓库中的html文件直接解析成页面？
settings -> source -> master branch

## 如何删除仓库
打开要删除的仓库，点击settings下拉到Danger Zone，点击delete this repository，将id名和仓库名写到空白的地方，点击确定即可

## Bash是什么操作系统的命令
linux

## Pwd是什么命令
是Print Working Directory的缩写，基本功能是打印当前的工作目录

## Cd是什么命令
显示当前目录名或改变当前目录  是change directory的缩写
ct是copy

## Echo是什么命令
打印 输出

## 配置git用户名的命令
$git config --global user.name ""

## 配置邮箱的命令
$git config --global user.e-mail ""

## 命令行换行方式
ctrl+/

## 命令行终结方式
ctrl+c

## 使用命令行比GUI方式有何优势
    命令行有些独特的好处：
   一是错误提示非常详细，详细到你知道错哪了，正确的用法是什么，一来二去很快就能熟悉
   二是写自动化脚本的时候，只能用命令行啊，比如自动测试和部署脚本，无论是shell脚本还是py脚本，GUI没法用

## 提交到本地仓库时为什么有暂存区
      工作区workspace和仓库之间有一个暂存区。
暂存区：英文叫stage, 或index。在版本库.git）目录下，有一个index文件。
它实际上就是一个包含文件索引的目录树，像是一个虚拟的工作区。
在这个虚拟工作区的目录树中，记录了文件名、文件的状态信息（时间戳、文件长度等），文件的内容并不存储其中，
而是保存在Git对象库（.git/objects）中，
文件索引建立了文件和对象库中对象实体之间的对应。如果当前仓库，有文件更新，
并且使用gitadd 命令，那么这些更新就会出现在暂存区中。

## 新建代码仓库的命令
 在当前目录新建一个Git代码库 : git init
 

## git clone [url] 这个命令的作用是
将仓库中的东西弄到本地文件夹中


## 添加指定文件到暂存区的命令
git add[file1][file2]

## 删除工作区文件，并且将这次删除放入暂存区的命令
git rm.

## 改名文件，并且将这个改名文件放入暂存区的命令
 git mv

## 提交暂存区到仓库的命令
 git commit -m[message]

## 直接从工作区提交到仓库的命令
git commit -a-m[message]

## 显示变更信息的命令
 git status

## 查看历史信息的命令
git log 




## Commit的意义是
  从暂存区往仓库中提交

## Pull的意义是
  将远程仓库的提交下到本地。

## Push的意义是
 将本地的提交推送到远程仓库。
