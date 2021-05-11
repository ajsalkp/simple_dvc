create env
'''bash
      conda create -n wineq python=3.7 -y
'''
activate env
```conda activate wineq
pip install -r requirements.txt
```
Download data and put inside give_data folder
from https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m 'first commit'

git remote add origin https://github.com/ajsalkp/simple_dvc.git
git branch -M main
git push origin main


