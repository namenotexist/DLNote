- 分支创建、删除、远程同步、解决冲突
    - 查看本地当前分支
        - git branch
    - 查看远程当前分支
        - git branch -r
    - 查看所有分支
        - git branch -a
    - 创建新的分支
        - git branch [brach name]
    - 切换新的分支
        - git checkout [branch name]
    - 创建新的分支并切换到该分支上面
        - git checkout -b [branch name]
    - 将新的分支推送到远程
        - git push origin [branch name]
    - 删除本地分支
        - git branch -d [branch name]
    - 删除远程分支
        - git push origin :[branch name]
    - 合并分支
        - git merge [branch name]
    - 解决冲突
        - 手动编辑解决冲突
        - git add & git commit
        - 查看分支合并图
            - git log --graph --pretty=oneline --abbrev-commit
    
- 全局配置
    - git config --global user.name 'Your name'
    - git config --global user.email 'email@example.com'
- 创建一个空仓库
    - git init
- 提交文件到仓库
    - git add file1.txt
    - git add file2.txt file3.txt
    - git commit -m 'add 3 files'
- 查看仓库状态
    - git status
- 查看具体哪些地方被修改
    - git diff [filename]
- 查看提交历史
    - git log --pretty=oneline
- 版本回退
    - git reset --hard HEAD^
- 版本跳转
    - git reset --hard [commit id]
- 查看命令历史
    - git reflog
- 工作区和版本库
    - working directory
    - repository
        - stage(暂存区)
- 撤销工作区的修改/删除(用版本库的版本替换工作区的版本)
    - git checkout --[filename]
- 删除文件
    - 工作区删除 rm [filename]
    - 版本库删除 git rm [filename]
- 添加并关联远程仓库和本地仓库
    - 本地建立一个仓库
    - github建立一个新的仓库
    - 把本地仓库的内容推送到远程仓库并关联
        - git remote add origin git@github.com:michaelliao/learngit.git
        - git push origin master
- 从远程库克隆
    - github建立一个仓库
    - 克隆到本地：git clone git@github.com:michaelliao/gitskills.git








