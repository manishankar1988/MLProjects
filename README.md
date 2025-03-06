create git hub respository MLprojects
create a project folder, using cmd create vscode instance MLPROJECTS
create a virtual Environment
conda create -p venv python==3.8 -y
conda init
conda activate venv
git add README.md
git commit -m "firts commit"
git status
git branch -M main
git config -- global user.name “manishankar1988“
git config --global user.email “manishankar1988@gmail.com“
git remote add origin https://github.com/manishankar1988/MLProjects.git
git push -u origin main
pip install -r requirements.txt
see that mlproject.egg-info created

Create a gitignore with python in github and commit
git pull
Create a Setup.py file 
and requirements.txt file
Create a folder src
in that create a file __init__.py
pip install -r requirements.txt

see that mlproject.egg-info created

create a folder components inside Src and __init__.py
add the Data ingestion 
data transformation
and model training 
then add pipeline folder
add __init__.py
add traning pipeline
and predict_pipeline

create three important files
logger
exception
and util
sys library  run time environment 


add code for exception
add code for logger
python src/logger.py 
see logs created


git pull origin main --rebase

take student perfomance data from kaggle

create a folder notebook
create a folder data
add stud.csv data

add to files one for EDa and other model training