# CBMI-eICU-EDA
The <b>t_sepsis onset.ipynb</b> file is where it all started. It is based on the demo eICU database. It contains all my data exploration attempts and the 3 timestamps (t_suspicion,t_sofa,t_sepsis) calculation.<br>
the <b>t_sus.ipynb</b> is the file where I have tested the actual database's microlab and medication dataset. This is where I have found many how little the microlab table is impacting the medication table in t_suspicion calculation.<br>
The <b>modification t_sepsis.ipynb</b> is where I have made adjustments and corrections on top of the t_sepsis onset file. I have made an attempt to integrate the culture parameter into the t_suspicion calculation. But to my dismay, there is no patient in the eICU demo file that is listed in the microlab table.<br>
The <b>graphing</b> file is for analysing control and cases in the database.<br>
