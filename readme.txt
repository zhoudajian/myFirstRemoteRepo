git��������

1�� git init			�ѵ�ǰĿ¼���git���Թ���Ĳֿ�
2�� git add filename		���޸ĺ���ļ���ӵ��ݴ���
3�� git status 			�鿴��ǰ״̬�Ƿ���δ�ύ��δ��ӵ��ݴ������ļ�
4�� git commit -m "�ύ����"	���ݴ������ļ��ύ�����زֿ�
5�� git diff �ļ���		�鿴�ļ��޸ĵ�����
6�� git log [--pretty=oneline]	�鿴��ʷ��¼
7�� git reset --hard HEAD^	���˵���һ���汾
8�� git reset --hard HEAD~n	���˵�ǰn���汾��nΪ������
9�� git reset --hard �汾��	���ݰ汾�Ż���
10��git reflog			�鿴�汾��
11��git checkout -- filename	�����ļ��ڹ������������޸�/�ָ�ɾ��(rm)��δcommit���ļ�
	1) �ļ���ûadd���ݴ����������޸ĺ�ص��Ͱ汾��һģһ����״̬
	2) �ļ��Ѿ�add���ݴ������ٴ��޸ģ�������ͻص�add�ݴ������״̬
12��rm file			ɾ���ļ�
13��ssh-keygen -t -rsc -C "youremail@example.com"	����ssh key
14��git remote add origin RemoteAddress			����Զ�ֿ̲�
	�ҵĵ�ַ��https://github.com/zhoudajian/myFirstRemoteRepo.git
15��git clone RemoteAddress	��Զ�̿�¡һ�����ذ汾��
16��git branch			�鿴��֧
17��git branch ��֧��		������֧
18��git checkout ��֧1		�ӵ�ǰ��֧�л�����֧1��
			      * �л��󣬹������ļ����ݱ�Ϊ��֧1���һ���ύ�����ݡ�
			      * ��ǰ��֧δ�ύ���ļ�������Ҳ�����л�����֧1�У�
			      * ��ĳ���ļ����ݱ��޸ĺ����֧1���ļ��г�ͻ�򱨴�
			      * �����ĸ���֧���ύ�ͱ�Ϊ�ĸ���֧�����ݣ������ٱ�������һ��֧��		
19��git checkout -b branchname	�������л���֧���൱��17��18�Ľ�ϣ�
20��git push -u origin branchname	������branchname��֧���µĴ������͵�Զ��branchname��֧(��һ����Ҫ-u, �Ժ���Ҫ)��
21��git pull origin ��֧��	��Զ�̷�֧��ȡ����
22��git merge dev		�ڵ�ǰ�ķ�֧�Ϻϲ�dev��֧
23��pwd				��ʾ��ǰĿ¼��·��
24��mkdir			�����ļ���
25��touch			�����ļ�
26��cat				�鿴�ļ�����
26��git stash			�ѵ�ǰ�Ĺ����������������Ժ�ָ��ֳ����������������bug�޸���
27��git stash list		�鿴���б����ص��ļ��б�
28��git stash apply		�ָ������ص��ļ����������ݲ�ɾ��
29��git stash drop		ɾ���ļ�
30��git stash pop		�ָ��ļ���ͬʱҲɾ���ļ�
31��git remote			�鿴Զ�̿����Ϣ
32��git remote -v		�鿴Զ�̿����ϸ��Ϣ
