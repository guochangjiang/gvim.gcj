# vim 插件说明
As I use vim frome 2 years ago. I have to copy my \_vimrc
## 说明

O这是一个集合我vim配置和插件配置的项目
## 1：\_vimrc
\_vimrc的配置需要自己精雕细琢。
## 2：perl-support
在原作者的基础上做一定的改动，以方便使用。
## Tabular
网址："http://www.vim.org/scripts/script.php?script\_id=3464
### 安装方法
把解压得到的文件godlygeek-tabular-1835018文件中的内容，直接复制到vimfiles里面。
### 使用方法
最简单的等号对齐的方法：
选中你要对齐的几行,然后按冒号:Tab/=
这样就可以对齐了
```
how = 1
thing= 2
```
对齐以后
```
how   = 1
thing = 2
```

## 自动补齐插件:AutoComplPop
网址：http://www.vim.org/scripts/script.php?script_id=1879
### 安装方法
将下载的文件放到vimfiles中，然后解压到当前文件夹，有重复的文件夹，选择合并文件夹。
### 使用方法
这个非常简单，你输入以后会自动补全。类似VS中的功能。

## NERD tree:文件中的浏览器
添加时间：2014-06-23
安装方法非常容易，下载以后解压到vimfiles就可以了。
Nerd tree 可以让你浏览文件系统并打开文件或目录。
### 绑定快捷键
在vmrc选中添加下面一行
nnoremap <silent> <F5> :NERDTree<CR>
### 使用方法简介
```
:NERDTree [|] # 打开一个Nerdtree,根节点由参数指定，不指定参数就是以当前目录为根节点
              # 也可以在文件和tree之间切换
:NERDTreeClose # 在当前Tab中关闭tree
o  # 在已有的窗口中打开文件、目录，或书签
go # 在已有窗口 中打开文件、目录或书签，但不跳到该窗口 |NERDTree-go|
t  # 在某个文件上按t，在标签页打开，并跳转到标签页
T  # 在后台标签页打开，不跳转过去
i  # split 一个新窗口打开选中文件，并跳到该窗口
gi # split一个新窗口打开选中文件，但不跳到该窗口
p  # 到上层目录
P  # 根目录
u  # 打开上层目录
m  # 显示文件系统菜单（添加、删除、移动操作）
q  # 在文件树中的时候，按q可以退出文件树
```
帮助文档在vimfiles/doc/NERD_tree.txt

## 关于学习手册
* Vim用户手册中文版
* Vi Improved.pdf
* vim-101-hacks.pdf
* Hacking vim.pdf
* 学习vi和vim编辑器\_中文版\_第7版.pdf
* Practical Vim Edit:at the Speed of Thought.pdf

所有上面的文件都可以在百度云:
http://pan.baidu.com/s/1xjpH7
如果文件因为内容没有审核通过，可以发邮件来索取。
