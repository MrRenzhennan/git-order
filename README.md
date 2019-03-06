# git-order
git常用命令


## 本地分支推远程分支
master 本地分支  
gh-pages 远程分支
```git
git push origin master:gh-pages
```
## 查看git配置
```
git config --system --list    查看系统config
git config --global  --list   查看当前用户（global）配置
git config --local  --list     查看当前仓库配置信息
git config  --list             查看全部
```
