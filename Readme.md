'''
conda create -n proj python=3.8 -y
conda activate proj
pip install -r requirements.txt
git init
dvc init
dvc add main.py
git add .
git commit -m "first message"
git remote add origin https://github.com/souravshukla/mlops.git
git branch -M main
dvc repro

'''