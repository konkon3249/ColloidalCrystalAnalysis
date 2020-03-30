# OpenCV-Python��p��������E�摜�������b�X��
## �` �R���C�h���q�̌�������p���� �`
by Kohei Ishikawa (aka konkon)  
E-mail: ishikawa@unno.material.nagoya-u.ac.jp

## �͂��߂�
���̃��|�W�g���́A�R���C�h���q�̌���������̉摜�������@��Jupyter-notebook�`���ł܂Ƃ߂����̂ł��B  
���ꂼ��̃m�[�g�u�b�N�̓��e�͈ȉ��̒ʂ�ƂȂ�܂��B  

1. MakeSample.ipynb - ���悩��̉摜�T���v�����O
2. ParticleDetection.ipynb - �R���C�h���q�̌��o�ƒ����ϐ��̉��
3. MovieAnalysis.ipynb - �摜�����E��͂̑S������

1�`3�̏��ɓǂݐi�߂Ă����΁A���悩��̉摜��͂̈�A�̗��ꂪ�킩��悤�ɂȂ��Ă��܂��B
�Ȃ��Ă���͂��ł�(��])�B

## ���\�z�̕��@
### Anaconda�̃C���X�g�[��
Python�̃C���X�g�[���ɂ́AAnaconda���g���̂��֗��ł��B  
https://www.anaconda.com/distribution/#download-section  
���URL����A���ɉ������C���X�g�[���[����肵�ē������Ă��������B
(�Ԉ���Ă�Python 2.x version���C���X�g�[�����Ȃ��悤��)  
  
�C���X�g�[�����@�͓K���Ƀl�b�g�ɓ]�����Ă�L�����Q�l�ɂ��Ă��������B  
https://ai-inter1.com/python-install/
������Ƃ��B

### Python���̍쐬
Anaconda�𓱓��ł�����AnacondaPrompt���N�����Ă��������B
<img src='./img/fig1.png'>
�R�}���h�v�����v�g���J���̂ŁA�ȉ��̂悤�ɓ��͂��Ă��������B

```
conda create -n "�D���Ȗ��O"
```

<img src='./img/fig2.png'>
"�D���Ȗ��O"���V�������̖��O�ɂȂ�܂��B�摜�ł�"colloid"�ł��B  
�G���^�[��������y/n�Ɗm�F�����̂�y�������ăG���^�[���Ă��������B  
���΂炭�����colloid�Ƃ������O��Python�����V�����\�z����܂��B  

### �F�X�ƃC���X�g�[��
���̂悤�ɂł������ɂ�Python���������ĂȂ��̂ŁA�K�v�Ȃ��̂��C���X�g�[�����܂��B
�܂��A�ȉ��̂悤�ɓ��͂��Ċ����N�����܂��B

```
activate "����"
```

����� activate colloid ��colloid �Ƃ������O�̊����N�����܂��B
����������A�ȉ��̂悤�ɓ��͂��ăG���^�[���Ă��������B

```
pip install numpy scipy scikit-learn scikit-image tqdm opencv-python notebook widgetsnbextension
```

���΂炭����ƕK�v�ȃp�b�P�[�W���C���X�g�[������܂��B  
��肪�N�����猠��������̖�肾�Ǝv���̂ŁAAnaconda Prompt���Ǘ��Ҍ����ŋN�����Ă��������x����Ă��������B  
����ł����܂������Ȃ��ꍇ�́A�G���[���b�Z�[�W��ǂ�ŗՋ@���ςɑΉ����Ă��������B  

### Jupyter-notebook�̃G�N�X�e���V������L����

�C���X�g�[�������܂���������A�ȉ��̂悤�ɓ��͂��Ď��s���Ă��������B

```
jupyter nbextension enable --py --sys-prefix widgetsnbextension
```

Jupyter-notebook��extention��L������������ł��B