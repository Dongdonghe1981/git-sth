# git-sth
git相关知识
基本信息设置
### 设置用户名
git config --global user.name "Dongdonghe1981"

### 设置用户邮箱
git config --global user.email "43654280@qq.com"

该设置在github仓库主页显示谁提交了该文件

### git search
>in:name spring boot stars:>3000 forks:>3000
><br/>in:readme spring boot stars:>1500
><br/>in:description spring 微服务 language:java pushed:>2019-09-01
><br/>in:description 爬虫 language:python stars:>1000 pushed:2019-02-01

### 初始化一个新的Git仓库
1.	创建文件夹
2.	在文件夹内创建git仓库 
>git init
3.	创建文件
4.	添加到暂存区
>git add 文件名
5.	将文件从暂存区提交到仓库
>git commit -m ‘add a file’
6.	删除文件
>git rm 文件名
>git commit -m ‘del a file’
7.	提交到远程仓库
>git push
clone到本地仓库
>git clone [path]

### 设置免用户名/密码提交
git config --global credential.helper store

### 首次提交
git remote add origin https://github.com/Dongdonghe1981/servlet3.0.git
git push -u origin master
