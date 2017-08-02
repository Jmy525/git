git is a version control system
git is a free software 
it's my life my decision
i want you with provision

分布式(区别集中式)版本控制系统，配置每个机器的家门
git config --global user.name "name"
git config --global user,email "email@example.com"

创建版本库
mkdir git
cd    git
pwd   
ls -ah

添加文件到版本库中
git add readme.txt
git commit  -m "本次提交说明"
--------------------------------
git status 查看仓库当前状态，内容是否变化等信息
git diff   查看仓库中和文件中不同的地方

再次提交继续调用add 和commit


git log查看历史提交记录
git回退版本，下面的HEAD^表示上1个。取值可以是HEAD~100
git reset --hard HEAD^   
git reset --hard 6570...回退到对应的版本
git reflog  记录历史中每次命令

git checkout 撤销修改

git rm test.txt  删除文件
git commit       确认删除
git checkout --test.txt恢复文件到最新版本


创建github

建立关联：git remote add origin git@github.com:Jmy525/gitstudy.git
第一次推送：git push -u origin master
以后提交：git push origin master
---------------------------------

从远程库克隆一个本地库
git clone https://github.com/Jmy525/git-study.git
		
test
test







