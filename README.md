# 今天学习了MarkDown
MarkDown是一种超文本语言今天我第一次学习它。
HelloMarkDown!
接下来我还会学习:
1. Git的基础命令
1. Hexo框架
1.Hexo更换主题
用命令行敲命令是一种**Geek**行为，我觉得还挺有趣的。
有点意思，下面这张gif可以形容我的心情:
![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)

Git提交的三部曲
（1）git add：使用命令 git add -A
（2）git commit 使用命令 git commit -m “本次提交的修改的备注”
新创建的文件1必须按照顺序进行提交，如果知识修改文件，并没有创建新文件，也可以使用
git commit -am “本次提交的修改的备注”来合并前两个步骤。
（3）git push 比较复杂分以下几种情形
        * 第一次提交到本分支
命令为：git push origin main 
  origin：远程仓库的默认名称。 main：是我们的分支名称（主分支）
        *第2-n次提交到本分支
命令：git push
        *提交到其他分支
用的较少，如果我们要提交到b分支，那么我们可以输入这个命令：
git push origin b

6、git pull
有时候出现本地仓库和线上仓库不一样的情况，比如本地的内容是【1，2】，线上的内容是
【2，3】这时使用git pull 抓取远程仓库的内容，抓取之后我们的本地内容变为【1，2，3】
命令：git pulll
这里1，2，3指的是文件夹
