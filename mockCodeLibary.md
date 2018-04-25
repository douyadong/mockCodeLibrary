# 模拟本地远程仓库及代码冲突
1. git init --bare aa.git (创建本地远程仓库即裸仓库，文件为aa.git,要带上git后缀)；

2. git init （创建本地仓库，可以提交到远程仓库）

3. git clone C:/Users/Administrator/Desktop/fff/aa.git(克隆远程仓库代码，此时地址要用/而不要用\这种，否则会造成失败，git基于linux,用\会有问题);
