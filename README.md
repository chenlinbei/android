# android
【git命令的使用】
1.复制项目
git clone "地址"

2.配置本地sshkey
ssh-keygen -t rsa -C "邮箱地址"

3.在github中设置后,验证是否配置成功
ssh -T git@github.com

4.配置username和email

git config --global user.name "用户名"
git config --global user.email "用户邮箱地址"

5.给本地仓库添加远程地址
git remote add origin git@https://github.com/chenlinbei/android.git

6.本地添加文件
git add README.md

7.本地提交
git commit -m "提交信息"
(如果没有添加提交信息,命令行会进入到linux vim 文本编辑器中,这时候需要使用vim各种命令 )

8.提交到远程仓库
git push origin master

9.导出到本地
git pull 


