git init
 // 初始化git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // 生产密匙


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub  //或者~/..sh


git config --global user.name "yuan"

git config --global user.email "yuan_guoan@163.com"

 git config --global push.default simple



git add .   // 当前目录下文件提交到缓存

 git commit -m "first commit" 创建commit

git remote add origin https://github.com/q315237943/TestDemo.git  // 远程代码仓库指向origin

git push // 推送代码到远程仓库
 git push --set-upstream origin master



eval $(ssh-agent -s)      //容易出问题的地方
ssh-add ~/.ssh/id_rsa  // 将密匙加入git


fgfgfgfgf



test111111

test2
