1.�޲z�s�զ@�θ�ƪ��v���]�p�G

�إ߸s�զW�٬��G mygroup, nogroup
groupadd groupname
�إ߱b���W�٬��G myuser1, myuser2, myuser3 �A�q�q�[�J mygroup�A�B�K�X�� MyPassWord
useradd -G groupname username
passwd username
�إ߱b���W�٬��G nouser1, nouser2, nouser3 �A�q�q�[�J nogroup�A�B�K�X�� MyPassWord
useradd -G groupname username
passwd username
�إߤ@�ӦW�� /srv/myproject ���ؿ��A�o�ӥؿ��i�H�� mygroup �s�դ����ϥΪ̧���ϥΡA�B�i�s�ت��ɮ׾֦��s�աj�� mygroup �C���L��L�H���঳�����v��
mkdir directoryname
chmod 770 directoryname
chgrp groupname directoryname
ll /srv�d�ݽT�{�@�U
�Ȯɤ������� myuser1 �������A�ëe�� /srv/myproject �ؿ��A���իإߤ@�ӦW�� myuser1.data ���ɮסA����n�X myuser1�C
su myuser1
cd
touch
exit
�_��/usr/bin/ls��/usr/local/bin/myls��A�����U�C�ާ@
cp
chmod g+s
ll �T�{
su nouser1

���M nogroup �s�դ����Τ��� /srv/myproject ���ӨS�������v���A���� nogroup �����Τ���� /usr/local/bin/myls ��
�A�i�H���ͻP ls �ۦP����T�A�B�Ȯɾ֦� mygroup �s�ժ��v���A�]���i�H�d�ߨ� /srv/myproject �ؿ������ɦW��T�C
�]�N�O���A��A�ϥ� nouser1 ����������imyls /srv/myproject�j�ɡA���ӬO����d�\��ӥؿ������ɦW��T�C

---------------------------------------���j�u-----------------------------------------

2.�ϥε{���[����O�A�f�t grep ������r�d�ߥ\��A�N��쪺 rsyslog �������{�Ǫ� PID, PRI, NI, COMMAND ����T��s�� /root/process_syslog.txt �ɮפ��C(�f�t>���ɦV��X)
ps aux | grep rsyslog > /root/process_syslog.txt

---------------------------------------���j�u-----------------------------------------

3.�ϥ� find ��X /usr/bin �� /usr/sbin ��ӥؿ����A�t�� SUID ���S���ɮ��ɦW�A�èϥ� ls -l �h�C�X��쪺�ɮת������v����A�N�ù������s�� /root/findsuidsgid.txt �ɮפ��C(�ۦ�d��find���O�Ϊk�A�H�Ψϳz�L���ɦV�Ÿ�>��X�ɮ�)
find /usr/bin -perm /u=s -exec ls -l {} \; > /root/findsuidsgid.txt 
find /usr/sbin -perm /u=s -exec ls -l {} \; >> /root/findsuidsgid.txt 


![]()

