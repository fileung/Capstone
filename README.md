# Capstone

Project Status: Incomplete, cancelled<br/>
<br/>
<b>Setup on Ubuntu</b><br/>
<br/>
Conda new environment<br/>
$conda create -n capstone python==3.5.2<br/>
$source activate capstone<br/>
<br/>
Install required packages<br/>
$conda install numpy scipy pandas matplotlib jupyter scikit-learn tqdm<br/>
$conda install tensorflow-gpu==1.12.0<br/>
$conda install keras==2.2.2<br/>
<br/>
Requirements file provided, not tested<br/>
environment.yaml<br/>
<br/>
Run notebook<br/>
$jupyter notebook<br/>
then follow the provided link in console<br/>
<br/>
Run Tensorboard to view model training performance<br/>
$tensorboard --logdir=logs/<br/>
<br/>
browse to<br/>
http://<your machine name>:6006<br/>
<br/>
to display all graphs<br/>
search: \w <br/>
