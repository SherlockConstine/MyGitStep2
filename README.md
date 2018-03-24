# MyGitStep2
* 1.勾选初始化README.md

* 2.cd F:/GitHub/mygit

* 3.git init

* 4.ssh -T git@github.com

显示：[Hi SherlockConstine! You've successfully authenticated, but GitHub does not provide shell access.]

* 5.git add test1.txt
    git add .


* 6.git status

（无）：
On branch master
nothing to commit, working tree clean

（更改）：
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

git config --global user.name "your name"
git config --global user.email "your_email@youremail.com"

* 7.git remote add origin git@github.com:SherlockConstine/MyGitStep2.git

掉线问题：
github可能会"掉线"。会报fatal: remote origin already exists.
git remote rm origin 
再输入：
git remote add origin git@github.com:SherlockConstine/MyGitStep2.git

* 8.挂github ：git push -u origin master


* 9.将远程代码库中的代码pull到本地代码库，并且执行合并merge：

$ git pull --rebase origin master
warning: no common commits
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:zuiwangzuo/myDemoPro
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
First, rewinding head to replay your work on top of it...
Applying: 提交初始代码。

* 10. 再次push代码：

$ git push origin master
Counting objects: 20, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (12/12), done.
Writing objects: 100% (20/20), 2.51 KiB | 0 bytes/s, done.
Total 20 (delta 0), reused 0 (delta 0)
To git@github.com:zuiwangzuo/myDemoPro.git
   8227f7c..aff8663  master -> master


我们看到本地代码已经成功的提交到远程代码中，至此问题解决。


