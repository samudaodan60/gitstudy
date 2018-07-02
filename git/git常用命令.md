# Git常用命令
## git diff彩色输出
git config --global color.ui auto
### 工作区与暂存区比较
git diff
### 暂存区与版本区比较
git diff --staged
### 版本区互相比较
git diff commit1 commit2
## git checkout
### 回退到过去版本，进行代码检查或者bug查找
git checkout old_commit_id
### 从旧的commit_id到最新的id
git checkout master  
[commitId生成细节](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)
## 分支
###  创建分支
git branch new_branch
### 切换分支
git checkout branch_name
### 创建并切换分支
git checkout -b new_branch
