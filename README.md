# SisterhoodHomework
## 0902

1）见document0902，python的基础语法

- 赋值和数据类型。

- for/while循环。

- if/else语句

  Homework: 求1到1000以内素数的和。

2）git的基础用法。

**git clone -b** <branch name> <repo link> :

​	从网页上下载仓库里的内容到当前文件夹里。（用的时候不需要加<>，我这里只是用这个符号注明这段内容你要改成相应的）。注意branch name是你要下载的那个branch的名字，repo link在仓库首页能找到。

**git branch** <new branch name>: 

​	新建一个branch，<new branch name>是你自己想要叫这个分支的名字。

**git checkout** <branch name>:

​	切换到某分支下。注意你新建一个新的分支后，当前的项目仍然停留在原来的分支下，如果这时候你提交改动，改动会提交到原本的分支。要先git checkout切换分支，然后再进行git add/git commit提交，改动才会被记录到新分支下。关于提交改动的内容会在后文进一步说明。

**git status**: 

​	查看文件的改动状态，会输出当前文件夹对比上一次使用git commit时有多少变化（这个指令我会在后面讲。）

**git add** <file name>:

​	将修改过的文件记录到储存区里。当你更新了文件内容之后，git不会立刻把它们记录下来。你要先git add 文件之后，git才会知道这些文件你修改过了。如果你想一次性把所有有改动的文件全部添加，使用**git add .** 这个指令即可。

**git commit**:

​	将刚才git add到储存区的文件全部提交到本地的分支里。这一步之后，会将你现在的文件状态在本地保存为新的节点。

**git push**:

​	刚才的git commit在本地生成了新节点，git push的意思是将这个新节点的状态保存到云端的仓库里。之前所有的操作都是关于你自己电脑上的备份，但这一步之后，你能在github上看到文件的变化。通常来说，你写完代码之后要保存到github，进行以下三步：git add, git commit, git push。
