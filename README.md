<h2> What is UNSW NB-15</h3>
<p><b>  Unsw Nb-15</b>dataset is a benchmark dataset used for network intrusion detection research. It was created by the Australian Centre for Cyber Security (ACCS) at the University of New South Wales (UNSW) in 2015. The dataset is designed to simulate real-world network traffic and to help researchers develop, test, and evaluate intrusion detection systems (IDS) and anomaly detection models.</p>

<p>The dataset is widely used in the academic community for cybersecurity-related research, particularly in building models that can identify and detect network intrusions or abnormal activities in network traffic.</p>


# UNSW-NB15-MachineLearning-and-DeepLearning
Assignment:- Find Attack class , accuracy score, precision score, F1 score, ROC and FPR using Decision Tree, Random Forest and Artificial Neural Network.
Here is an python file which comprises of ML and DL algorithms which are used on the training and testing sets of UNSW-NB15 dataset.

<img src="https://github.com/HanumatNegi/UNSW-NB15-MachineLearning-and-DeepLearning/blob/6c5545c6992d23e9b401e8b2c8d5cbe25ee02bee/images/ai.jpg">

ML algorithms used:- Decision Tree Classifier, Random Forest Classifier


DL algorithms used:- Artificial Neural Network

<h4>Attack Class</h4>
"attack_cat" aka <u>Attack Class</u> of the Dataset of UNSW NB-15 contains different elements which are <b>normal</b> and <b>anomalies</b>.
The attack class are counted using <b>dataset.values_count();</b> funstion of <b>pandas library</b>.

The Elements of Attack class are as follows:-

Normal            37000
Generic           18871
Exploits          11132
Fuzzers            6062
DoS                4089
Reconnaissance     3496
Analysis            677
Backdoor            583
Shellcode           378
Worms                44

<img src="https://github.com/HanumatNegi/UNSW-NB15-MachineLearning-and-DeepLearning/blob/77d2f930c8d217d111f161881fa31dc716fc2796/images/Attack.png">
