# git command reference url
  - https://www.edureka.co/blog/git-commands-with-example/
  - https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
  - https://www.bookstack.cn/read/git-tutorial/docs-basic.md
# git flow 
  - config
  ```sh
  git config --global user.name "Some One"
  git config --global user.email "someone@gmail.com"
  ```
  1. git init：新建一个git库
  2. git status：查看目前状态
  3. git add <文件名>：添加文件从工作区到暂存区
  4. git commit -m “提示信息”：从暂存区提交到代码仓库
  5. git log：查看提交commit的信息
  6. git remote add origin https://github.com/try-git/try_git.git : 添加远程指针
  7. git push -u origin master：将本地的master分支推送到远程origin主机，-u参数表示记住对应关系，下次可以直接git push推送。
  8. git pull origin master：将远程主机origin的代码取回本地，与本地的master分支合并
  9. git diff HEAD：查看与上一次commit的区别
  10. git push -f origin master: 强推送
  
  # git issue
  1. fatal: Authentication failed ---- Windows Credentials Manager -> Edit -> Update pwd
  
  # git log
  1. git log --pretty=format:"%s" 信息标题 [reference doc](https://ruby-china.org/topics/939) 
  ```sh
  git log --pretty=tformat:"%h %ad | %s%d [%an]" --graph --date=short
  ```
