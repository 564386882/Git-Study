# Git-Study

## Git命令

`git clone` : 拉取git代码

`git checkout <branchName>` ： 创建分支（针对已存在的分直会切换过去）

`git checkout -b <branchName>`：创建分支并切换到此分支上

`git merge bugFix`：当前分支合并bugFix分支（创建新节点去指向当前分支和bugFix分支）

`git rebase bugFix`： 当前分支合并bugFix分支（将当前分支的节点移动到bugFix分支之后，线性流程）
