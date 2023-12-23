```C
// 在当前目录中创建一个Git仓库
git init 

// 将当前工作目录中的所有文件和目录添加到 Git 暂存区（staging area）。这个命令将所有未被忽略的文件都添加到暂存区，使它们成为下一次提交的一部分。
//如果你只想添加某个特定文件，可以使用 git add filename，其中 filename 是你想要添加的文件名。
git add * 

// 将当前暂存区中的更改提交到本地 Git 仓库，并附带一条简短的提交消息
// 包括提交的哈希值、作者、日期等
git commit -m "first commit"
  
备注：在.git中配置文件（config）书写[user] emali = 1306956287@qq.com name = soft-air

// 用于将远程 Git 仓库与本地仓库关联。
// 这个命令添加了一个远程仓库的别名，通常这个别名被命名为 origin，但你也可以选择其他名字。
// origin 别名用于指代远程仓库的位置。
// 关联远程仓库后，你就可以使用 git push 将本地仓库的更改推送到远程仓库。
// 以及使用 git pull 从远程仓库拉取更改到本地仓库。
git remote add origin https://github.com/soft-air/learn-c-plus-plus.git

// 将本地的 master 分支的更改推送到与之关联的远程仓库（origin）的 master 分支
git push -u origin master
```



```C
// 在你要保存的文件夹中，右键打开“open git bash here”
// 克隆这个网址中项目的所有分支到本地
git clone https://github.com/soft-air/learn-c-plus-plus.git 
```



```C
// 上传单个文件时，在修改文档的目录下进行操作；
// 上传多个文件时，可以直接在文件的总源头处操作，git add *
git add 123.txt // 例如就这个文件修改了，我要重新上传它到github

git commit -m "第二次修改后上传" // 备注信息
  
git remote add origin https://github.com/soft-air/learn-c-plus-plus.git // 
```



