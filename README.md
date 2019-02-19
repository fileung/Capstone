# Capstone

Project Status: Incomplete, cancelled<br/>
<br/>
Setup on Ubuntu<br/>
<br/>
Conda new environment<br/>
$conda create -n capstone python==3.5.2<br/>
$source activate capstone<br/>

Install required packages
$conda install numpy scipy pandas matplotlib jupyter scikit-learn tqdm
$conda install tensorflow-gpu==1.12.0
$conda install keras==2.2.2

Requirements file provided, not tested
environment.yaml

Run notebook
$jupyter notebook
then follow the provided link in console

Run Tensorboard to view model training performance
$tensorboard --logdir=logs/

browse to
http://<your machine name>:6006

to display all graphs
search: \w 
