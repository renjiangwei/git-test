# git branch 
## 创建新分支
git branch newBranch
git checkout newBranch

git checkout -b newBranch

## git push
git push origin feature-ts:feature-ts
git push origin 本地分支:远程分支

git push -u origin feature-ts
将本地分支推送到远程分支，如果远程分支不存在则创建，并关联