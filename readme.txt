git init
 // ��ʼ��git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // �����ܳ�


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub  //����~/..sh


git config --global user.name "yuan"

git config --global user.email "yuan_guoan@163.com"

 git config --global push.default simple



git add .   // ��ǰĿ¼���ļ��ύ������

 git commit -m "first commit" ����commit

git remote add origin https://github.com/q315237943/TestDemo.git  // Զ�̴���ֿ�ָ��origin

git push // ���ʹ��뵽Զ�ֿ̲�
 git push --set-upstream origin master



eval $(ssh-agent -s)      //���׳�����ĵط�
ssh-add ~/.ssh/id_rsa  // ���ܳ׼���git


fgfgfgfgf



test111111

test2
