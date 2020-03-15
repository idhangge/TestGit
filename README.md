# TestGit
新建仓库
git init
git status查看状态        指定文件的添加，比如：git add test.java
git add .        （注：别忘记后面的.，将当前目录所有文件提交本地git仓库）
git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）
//本地的仓库关联到GitHub
git remote add origin https://github.com/idhangge/TestGit.git
git pull --rebase origin master
git push -u origin master

更新仓库(文件夹下有.git文件夹)
git add *
git commit -m "更新说明"
git pull
git push -u origin master   

没有.git文件夹
把github上面的仓库克隆到本地
    git clone https://github.com/idhangge/TestGit.git
.git都复制到项目文件夹下面
