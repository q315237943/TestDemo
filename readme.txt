git init
 // 初始化git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // 生产密匙, 直接找到并打开..ssh文件夹下的公钥id_rsa.pub文件，复制；id_rsa为私钥


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub  //或者~/..sh


git config --global user.name "yuan"

git config --global user.email "yuan_guoan@163.com"

 git config --global push.default simple



git add .   // 当前目录下文件提交到缓存

git commit -m "first commit" 创建commit

git remote add origin git@github.com:q315237943/TestDemo.git  // <name><url>，添加远程库
//git remote rm origin 删除

git remote -v                    //查看仓库origin 类型


git push // 推送代码到远程仓库
git push --set-upstream origin master  //出现rejected,使用 git push --force --set-upstream origin master



eval $(ssh-agent -s)      //容易出问题的地方，启动ssh -agent，不然会ssh-add失败
ssh-add ~/.ssh/id_rsa  // 将私钥加入git


创建新仓库并推送文件：
1、github 创建远程仓库：注意，github网页操作，访问形式设置为ssh，复制ssh远程地址（git@github.com:q315237943/pylearning.git）

2、指向远程仓库：git remote add origin git@github.com:q315237943/pylearning.git

3、将远程分支（origin）设置为上游分支：git push --set-upstream origin master	
//origin为远程分支名，master为本地分支名。push时需要和远程仓库通信，此时如没有ssh则需要输入密码；因此需要生成密钥ssh，并在github添加，见前文。

4、push更新：git add . ->  git commit -m "comments"  ->git push