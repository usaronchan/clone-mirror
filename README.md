# Clone Mirror

该项目是通过 GitHub Action 来镜像境外的仓库同步到国内平台。

在 GitHub、GitLab 等国外的 Git 代码托管平台有很多国内用户经常需要拉取的仓库，但由于一些众所周知的原因，国内用户并不能很顺利地从这些境外平台上拉取仓库。

这个项目主要是记录并设置自动化工作流来同步镜像境外的仓库到国内平台，方便国内用户通过国内平台的镜像来拉取。

- 镜像同步频率：依照项目更新频率而定，一般来说是一星期或一个月同步镜像一次。如果是频繁更新的话，会设置每天同步

## 镜像同步的仓库

每周一同步：

- [LazyVim](https://github.com/LazyVim/LazyVim): `git clone https://gitee.com/clonegege/lazyvim.git`
- [lazy.nvim](https://github.com/folke/lazy.nvim): `git clone https://gitee.com/clonegege/lazy.nvim.git`

## 其他镜像项目

以下是国内一些平台上比较大的镜像项目。如果在以下平台能找得到同样的项目，这里就不再重复镜像同步

- https://gitee.com/mirrors

## 免责申明

- 这里镜像的是原始仓库的全部内容，仅仅是为了方便国内用户的拉取，没有其他任何目的
- 如果被镜像仓库的负责人认为该项目的行为是侵权的，可以提 Issues 或直接通过联系邮箱来联系我进行删除
