# 关于贡献GitHub

`main`为主分支，是一个受保护的分支，任何人不应该直接在此分支上修改代码并push（即便是仓库拥有者也不要随便这样做）。

## 作为仓库管理者

0. **必须**把主分支设定保护规则，不保护主分支是一件危险的事情。比如：每次PR必须有人review或者approve。

1. **禁止**不经过审查就随意合并PR。

2. **尽量**不要自己合并自己的代码。

## 作为贡献者

当你想向一个仓库贡献代码时，必须从主分支切出一个自己的开发分支，请遵循以下步骤：

0. fork一个项目到自己的GitHub

    此步骤免去原作者添加公钥。

1. git clone https://github.com/xxx

   这个地址时自己那个仓库的地址，此时会把仓库克隆到本地磁盘中（如果已经克隆了，请忽略），然后进入项目目录。

2. git checkout main

   把当前分支切换到 `main` 分支

3. git pull

   拉取 `main` 分支的最新代码（**务必**）

4. git checkout -b feat/test

   这条命令代表从当前分支（也就是 `main` 分支）切出一个新的分支叫做 `feat/test`，此时两个分支代码一模一样。

   此时使用`git branch`命令查看就是新的分支名称：`feat/test`

5. 写完代码后，执行 `add` 和 `commit` 命令，然后直接输入 `git push`，此时终端会给一个如下的提示：

   ```
   $ git push
   fatal: The current branch feat/test has no upstream branch.
   To push the current branch and set the remote as upstream, use
   
       git push --set-upstream origin feat/test // 复制这一行
   
   To have this happen automatically for branches without a tracking
   upstream, see 'push.autoSetupRemote' in 'git help config'.
   ```

   这个提示的意思是远端没有一个名为`feat/test`的分支，因为我们这是在 `feat/test` 分支上第一次向远端 push，此时只需要在中终端执行`git push --set-upstream origin feat/test`就可以把代码推送到远端了，以后再在 `feat/test` 分支改代码之后做push操作时就不需要输入这么长了，只需要`git push`即可。

6. 去自己github的项目主页提交 `pull request`并让管理者审查并合并代码。

