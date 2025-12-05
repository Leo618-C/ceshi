# 指令
## 创建仓库
1、绑定用户：
git config --global user.email "" 与git config --global user.name

2、设置ssh key：
首先检查是否已生成密钥 cd ~/.ssh，ls如果有2个文件，则密钥已经生成，id_rsa.pub就是公钥

也可以打开我的电脑C:\Users\Y\ .ssh 里面找到

如果没有生成，那么通过$ ssh-keygen -t rsa -C “xxxxxx@163.com”来生成。生成后复制到GitHub中

3、git init建立本地仓库

4、git add*把文件加入库

5、执行指令：git commit -m "提交文件"其中双引号内是提交注释。

6、在github上复制仓库ssh地址，使用git remote add origin git@github.com:gain-wyj/wyj_first.git命令关联仓库

7、git push -u origin main上传本地代码