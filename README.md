# Capstone

<h4>Project Status: Passed</h4><br/>
1. Proposal: Passed<br/>
2. Code in Notebook: Passed<br/>
3. Project Report: Passed<br/>
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
http://&lt;your machine name&gt;:6006<br/>
<br/>
to display all graphs<br/>
search: \w <br/>
<br/>
<b>Data</b><br/>
The csv files were located in /data/minute/<br/>
but the csv files are over 25MB and too large to upload.<br/>
please download the csv file for free at:<br/>
  http://www.cryptodatadownload.com<br/>
<br/>
Direct links to download:<br/>
  http://www.cryptodatadownload.com/cdd/gemini_BTCUSD_2018_1min.csv<br/>
  http://www.cryptodatadownload.com/cdd/gemini_ETHUSD_2018_1min.csv<br/>
<br/>
  
