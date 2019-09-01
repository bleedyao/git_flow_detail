# git flow 是什么？

git flow 是由 Vincent Driessen 创建的 git 的分支模型。它吸引了很多关注，因为它非常适合协作和扩展开发团队。
ps: 本质上，git flow 是 git 的一种扩展，轻松的分离了开发分支，功能分支，发布分支，热修复分支，给 git 提供高质量的分支操作

# git flow 怎么用？

* git flow init: 初始化仓库
* git flow feature start: 基于 dev 分支创建新的功能分支
* git flow release start: 基于 dev 分支创建新的发布分支
* git flow hotfix start: 基于 dev 分支创建新的热修复分支

# git flow 实战
## case 1: 在已有的项目中集成 git flow
## case 2: 多人并行开发
## case 3: 多人同时开发同一个分支