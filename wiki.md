'''
conda create -n keras_env keras    #keras가 설치된 'keras_env'이름의 env 만들기
conda env list    #env 목록 확인하기
activate keras_env    #'keras_env' 활성화하기
conda install jupyter notebook    #jupyter notebook은 따로 설치해야한다.
conda install matplotlib    #matplotlib 따로 설치해야한다.
pip install pydicom    #pydicom 따로 설치해야 한다.
'''
---
![search](./image/1.png)
---
![jupyter](./image/2.png)
---
```
conda update conda
conda install PACKAGE
conda update PACKAGE

conda create —name ENVNAME python=3.6
conda create —clone ENVNAME —name ENVNAME
conda env remove —name ENVNAME

conda env list
activate ENVNAME
conda list

condal install PACKAGE    #tensorflow keras numpy matplotlib
pip install PACKAGE    #pydicom
```

```python
!nvidia-smi
!pip freeze

from google.colab import drive
drive.mount(‘/content/gdrive/’)

import os
import shutil
os.chdir(‘???’)
!pwd    #print working directory
```
