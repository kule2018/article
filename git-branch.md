## git分支

git 的优势：

1.创建的分支轻量

2.创建的分支速度快，几乎瞬间完成

3.便捷的在不同的分支之间切换


git鼓励在工作流程中频繁地使用分支和合并 

### 分支创建

git branch [分支名字]

注：git中的HEAD指针可以让我们知道当前所在的本地分支

### 分支切换

git checkout [分支名字]

### 项目分叉历史

git log --oneline --decorate --graph --all

注: Git 的分支实质上仅是包含所指对象校验和（长度为 40 的 SHA-1 值字符串）的文件，所以它的创建和销毁都异常高效。创建一个新分支就相当于往一个文件中写入 41 个字节（40 个字符和 1 个换行符）