print ('Mar 27 2020')
git init
 // ��ʼ��git

ssh-keygen -t rsa -b 4096 -C "yuan_guoan@163.com" // �����ܳ�


 /c/Users/Administrator/.ssh

cat  /c/Users/Administrator/.ssh/id_rsa.pub


git config --global user.name "yuan"		//��ʾ������

git config --global user.email "yuan_guoan@163.com"	//��ʾ������

git config --global push.default simple



git add .   // ��ǰĿ¼���ļ��ύ������

git commit -m "��һ���ύ����"    //����commit, -m ����Ϊ�����ύ��˵��

git remote add origin git@github.com:q315237943/TestDemo.git  
// ���ƣ�origin��Ŀ��git@github.com:q315237943/TestDemo.git��git remote rm origin ɾ��

git push // ���ʹ��뵽Զ�ֿ̲�
git push --set-upstream origin master



eval $(ssh-agent -s)      //���׳�����ĵط�
ssh-add ~/.ssh/id_rsa  // ���ܳ׼���git


fgfgfgfgf



test111111
