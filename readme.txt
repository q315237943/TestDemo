20200401
git init
 // 初始化git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // 生产密匙, 直接找到并打开..ssh文件夹下的id_rsa.pub文件，复制密钥


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub  //或者~/..sh


git config --global user.name "yuan"

git config --globagitl user.email "yuan_guoan@163.com"

 git config --global push.default simple



git add .   // 当前目录下文件提交到缓存

git commit -m "first commit" 创建commit

git remote add origin git@github.com:q315237943/TestDemo.git  // <name><url>
//git remote rm origin 删除

git remote -v                    //查看仓库origin 类型


git push // 推送代码到远程仓库
git push --set-upstream origin master  //出现rejected,使用 git push --force--set-upstream origin master



eval $(ssh-agent -s)      //容易出问题的地方，启动ssh -agent，不然会ssh-add失败
ssh-add ~/.ssh/id_rsa  // 将私钥加入git


fgfgfgfgf



test111111

test2