* ���ϥ�
">" ���ϥ�
![]()
`���Ϊk
�ť|�Ӧ��t�@�إΪk
### �Х�ӽҰ�W�m�ߡA�z�Lsystemd�޲z�G��sshd�A�ȡA�����ĤG��sshd�A�Ȫ� port ���� 2222�C
### ������i�H�ϥΫ��O netstat -alntp | grep ssh �T�{�O�_�ҰʤG��sshd�A�ȡA�d�Ҧp�U�G

` $ netstat -alntp | grep ssh `
` tcp        0      0 0.0.0.0:22     0.0.0.0:*     LISTEN      1300/sshd `
` tcp        0      0 0.0.0.0:2222   0.0.0.0:*     LISTEN      15275/sshd `
` tcp6       0      0 :::22          :::*          LISTEN      1300/sshd `
` tcp6       0      0 :::2222        :::*          LISTEN      15275/sshd `

1.���]�wssh�s���𪺳]�w��
�ƻs�@����s����2222

2.�A���ssh���]�w�}��
�ƻs�@���N�Y���e�令�B�J�@�o��o�]�w�ɦW