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

## git revert
反转操作
1. push了一些代码，发现不该提的: git revert 提交id
2. 合并了一个分支，发现该分支有bug，需要取消该合并: git revert -m 1 合并id
3. 

## git reset
重置操作
1. push了一些垃圾代码，想直接放弃代码， reset 想回滚目标版本id
2. 

## git checkout 
1. 工作区代码还没add时，想放弃修改 git checkout . or git checkout filename
2. 工作区代码add了，想放弃添加缓存区 git add.之后 git reset filename HEAD 此时filename被移出缓存区，可以选择git checkout操作放弃修改
3. 

## git clean 
git clean -xdf 清除新增文件
