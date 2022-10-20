git bash --> code .
source C:/Users/Owner/anaconda3/Scripts/activate base

Create environment - 

conda create -n liveapp python=3.8.8 -y

Activate environment -

conda activate liveapp

Create and Install requirements - 
touch requirements.txt
pip install -r  requirements.txt

Create andd in README.md
touch README.md
history
Copy-Paste the commands in README.md file

Create python file
touch template.py
add the code according to video - https://www.youtube.com/watch?v=n4sz9cG_B7k&list=PLZoTAELRMXVOk1pRcOCaG5xtXxgMalpIe&index=5

mkdir data_given
paste winequality.csv file

Download the data from 
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init

dvc init

dvc add data_given/wine_quality.csv #When you want your data to be tracked for all the changes

git add . #To add the data in the staging area

git config user.email "museychamp@gmail.com"
git config user.email "mustafamadraswala"
git commit -m "first commit"
git add . && git commit -m "update README.md"

Create a repo on github - simple_dvc_demo
push an existing repository from the command line
git remote add origin https://github.com/mustafamadraswala/simple-dvc-demo.git
git branch -M main
git push -u origin main

link - https://github.com/mustafamadraswala/simple-dvc-demo

