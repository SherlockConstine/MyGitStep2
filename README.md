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



