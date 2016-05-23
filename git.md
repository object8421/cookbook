# Git

本文描述团队协作中使用的 Git Workflow，我们的 Git Workflow 是基于 [git-flow](https://github.com/nvie/gitflow) 建立的，你可以访问链接获得更多的资料。

## 分支

主分支：

- master：永远处在可发布状态，需要开启分支保护，不接受直接 push commit，只接受 Pull Request（以下简称为 PR）。
- develop：最新的开发状态，原则上不接受直接 push commit，大部分情况从 feature 分支合入代码。

辅助分支：

- feature：开发新功能的分支，基于 develop，完成后 merge 回 develop。
- release：准备要发布版本的分支，用来修复 bug，基于 develop，完成后 merge 回 develop 和 master。
- hotfix：修复 master 上的问题，等不及 release 版本就必须马上上线，基于 master，完成后 merge 回 master 和 develop。

![](http://7xj0bf.com1.z0.glb.clouddn.com/16-5-23/34304852.jpg)

## 开发流程

1. 从 develop 新建 feature 分支；
2. 提交 Commits；
3. Push Commits；
4. 发起 feature 分支到 develop 的 PR；
5. 合并分支；
6. 新建 release；
7. 修复 release 上的 bug；
8. 发布 release，merge 至 develop 和 master。

## 工具

你可以试用 Git 图形界面客户端 SourceTree 来进行日常 Git 工作，SourceTree 已经内置了对 git-flow 的支持，具体试用可以自行查阅资料。

## 一些约定

- 分支名建议试用有意义的英文，次级建议试用拼音，不建议使用中文。
- Commit 时请尽量使用中文。
- 一个分支尽量避免过多修改，可避免过多冲突；