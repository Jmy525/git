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







