* ���ϥ�
">" ���ϥ�
![]()
�ť|�Ӧ��t�@�إΪk

### 1.apache log�Oapache web server����x��

### �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC

### �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C

    yum -y install wget �U��wget
    wget �O�b�i��"�������"�����o�A�y�k: wget [-option] [url]
![1]()
![2]()

` wget https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log `
    �|���ͥX�@��web.log�ɡA�̭����Ҧ������
    
    �ڭ̳z�L cat web.log | grep error ���L��Xerror����T�C


### 2.tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C
### �btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC

    tar �u�ॴ�]�������Y�A�ݭn�g�Ltar�A�g�Lgzip or bzip2���榡���Y�C

![3]()