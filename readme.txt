# 2022/07/16 Yasushi Ohsugi
#
# readme.txt
#

�e�����̏ڍׁA���́E�o�̓t�@�C���ɂ��ẮA
�ʎ����uPySI ��v�����v���Z�X�@�ꗗ.pdf�v���Q�ƁB


# ******************************
# �p�b�P�[�W PySI_V0R2SC_ini_P�@�T�v���C�`�F�[���p�̏������̐������@
# ******************************
�y���������z

1. PySI_create_node_dir_copy_prof.py���N�������
   PySI��SCMTREE�p�̏������𐶐�����B

��)���ׂĂ�node�f�B���N�g���[�������ݒ肷��̂ŁA�v���ӁB
   �ғ����Ă�����ł͂Ȃ��A�V�����f�B���N�g�����쐬���ď���������̂��]�܂���


   1-1. �e���Ƌ��_��node���̃f�B���N�g����mkdir�ō쐬����B

   1-2. PSI��3�̃@�C����copy����B
   �f�B���N�g��.\\data����3���o�̓t�t�@�C����\node_all���̊e\node����copy����
   PySI_data_std_IO.csv
   PySI_Profile_std.csv
   PySI_monitor.xlsx

   1-3. �e���Ƌ��_��node���ɒ�`���ꂽPSI�v��p�����[�^profile�̃T�}���[�\
        "SCMTREE_profile010.csv"��ǂݍ���ŁA
        \node_all�̉��̊eprofile��copy����
   


# ******************************
# �p�b�P�[�W PySI_V0R2SC_main_P�@�ŏI����n�̎��v�f�[�^������main�̋N�����@
# ******************************
�y�ŏI���v�n(=LEAF NODE)�̎��vS�𐶐�����z

1. PySI_make_S_month2week.py���N������
   �ŏI���v�n(=LEAF NODE)�̌��ʎ��vS month���T�ʎ��vS week�ɕϊ�����


2. PySI_set_Leaf_Node_week_S2PSI.py���N������
   �ŏI���v�n(=LEAF NODE)�̏T�ʎ��vS week��
   �enode����PySI_data_std_IO.csv��S��copy����

   ��) PySI_data_std_IO.csv�̒���node_from ��node_to�́A
       ���̏�������profile�Œ�`���ꂽnode���ɍX�V�����


�y�T�v���C�`�F�[����PSI�v��A�g�z

1. PySI_main_SCMTREE_060_episode3_GC.py���N������
   �T�v���C�`�F�[���̍ŏI���v����}�U�[�v�����g�܂�PSI�v���A�g����

   ��) PySI_data_std_IO.csv�̒���node_from ��node_to�́A
       ���̏�������profile�Œ�`���ꂽnode���ɍX�V�����

   \node_all���̊e\node����"PySI_data_std_IO.csv"��PSI�v��Ƃ��čX�V�����B


�yPSI�v��̃O���t�\�� excel�z

1. \node_all���̊e\node���̉��L��3�t�@�C����excel�ŊJ���ƁA
   PySI_monitor.xlsx��PSI�O���t���\�������B

   PySI_data_std_IO.csv
   PySI_Profile_std.csv
   PySI_monitor.xlsx


�yPSI�v��p�����[�^�̈ꊇ�X�V��PSI�v��A�g�̋N�����@�z

1. PSI�v��p�����[�^�̈ꊇ�X�V�p�̈ꗗ�\"SCMTREE_profile010.csv"���g���āA
   �enode��PSI�v��p�����[�^���Z�b�g����

2. PySI_update_node_all_profile010.py���N������ƁA
   �enode����PSI�v��p�����[�^���ꊇ�X�V�����

3. PySI_main_SCMTREE_060_episode3_GC.py���N������
   �T�v���C�`�F�[���̍ŏI���v����}�U�[�v�����g�܂�PSI�v�悪�A�g���������

�ȏ�Aend of readme.txt

