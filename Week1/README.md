- [Week1](#week1)
  - [Git&Github操作指南](#gitgithub操作指南)
  - [预习 第1课 | 数据结构与算法总览](#预习-第1课--数据结构与算法总览)
  - [预习 第2课 | 训练准备和复杂度分析](#预习-第2课--训练准备和复杂度分析)
  - [第1周 第3课 | 数组、链表、跳表](#第1周-第3课--数组链表跳表)
  - [第1周 第4课 | 栈、队列、优先队列、双端队列](#第1周-第4课--栈队列优先队列双端队列)

#  Week1
## Git&Github操作指南
[作业提交流程](https://shimo.im/docs/m5rtM8K8rNsjw5jk/)
1.fork仓库
2.本地新建一个文件夹，'git init'命令初始化仓库
3.配置Git，进行配置用户名和邮箱：
`git config --global user.name "用户名"`
`git config --global user.email "邮箱"`
查看配置：
`git config --global --list`
4.配置公私钥
`ssh-keygen -t rsa -C "你的邮箱”`
配置保存公私钥的文件的名称，回车即表示默认，后续输入密码也可以输入密码，但要记住这个密码，不想输入密码可以直接回车，然后就创建成功。
进入刚才提示创建的文件夹，发现两个文件，id_rsa为私钥，id_rsa.pub为公钥，回到GitHub点击右上角头像Settings，点击SSH and GPG keys,在Key中将公钥文件内容完全复制进来。输入`ssh -T git@github.com`验证是否配置成功
5.克隆仓库
通过SSH，Clone到本地
6.提交代码
`git add .`命令将代码从工作区移到暂存区
`git commit -m "注释"`更新注释，将文件从暂存区提交到仓库区
`git push -u origin master`命令，将本地的master分支推送到origin主机
7.将该周作业链接，按格式跟帖进行comment贴到班级仓库对应学习周的issue下面

## 预习 第1课 | 数据结构与算法总览

##  预习 第2课 | 训练准备和复杂度分析

## 第1周 第3课 | 数组、链表、跳表

## 第1周 第4课 | 栈、队列、优先队列、双端队列