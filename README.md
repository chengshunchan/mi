# mi
1 打开cmd ，选择文件存储的盘符 e:
2 将文件的路径复制进来 cd E:\Html Project (cd + 路径)
3设置用户名 git config --global user.name '用户名'
4设置邮箱 git config --global user.email '邮箱名'
5 查询是否设置成功 git config -l
(显示刚刚设置好的用户名和邮箱) 
6 初始化 git init
7与我们的git连接起来
将我们的git地址粘贴过来 git remote add origin + git地址 （git remote add origin https://github.com/chengshunchan/mi.git）
8 在我们的文件夹里添加 文件夹和文件
9 在我们的本地的服务器查看文件夹和文件是否已经生效了  git status  (红色字体显示)
10 往我们的git 里添加  git add *
git commit -m 'first_commit'   (第一次连上)

11 将我们的文件上传到git官网上 git push -u origin master


