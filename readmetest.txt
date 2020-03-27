print ('Mar 27 2020')
git init
 // 初始化git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // 生产密匙


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub


git config --global user.name "yuan"		//显示的名字

git config --global user.email "yuan_guoan@163.com"	//显示的邮箱

git config --global push.default simple



git add .   // 当前目录下文件提交到缓存

git commit -m "第一次提交测试"    //创建commit, -m 后面为本次提交的说明

git remote add origin git@github.com:q315237943/TestDemo.git  
// 名称：origin，目标git@github.com:q315237943/TestDemo.git，git remote rm origin 删除

git push // 推送代码到远程仓库
git push --set-upstream origin master



eval $(ssh-agent -s)      //容易出问题的地方
ssh-add ~/.ssh/id_rsa  // 将密匙加入git


fgfgfgfgf



test111111
