# CBMI-eICU-EDA
<p>The <b>t_sepsis onset.ipynb</b> file is where it all started. It is based on the demo eICU database. It contains all my data exploration attempts and the 3 timestamps (t_suspicion,t_sofa,t_sepsis) calculation.</p>

<p>the <b>t_sus.ipynb</b> is the file where I have tested the actual database's microlab and medication dataset. This is where I have found many how little the microlab table is impacting the medication table in t_suspicion calculation.</p>

<p>The <b>modification t_sepsis.ipynb</b> is where I have made adjustments and corrections on top of the t_sepsis onset file. I have made an attempt to integrate the culture parameter into the t_suspicion calculation. But to my dismay, there is no patient in the eICU demo file that is listed in the microlab table.</p>

<p>The <b>graphing</b> file is for analysing control and cases in the database.</p>

<b>The Labs ready, Final Table build and cardiovascular parameters</b> are processed tables, based off the eICU original database. All these tables are being created to finally merge into a single table to train a model on top.</p>
<p>The <b>GCS Scores table and Labs Before FiO2</b> table works on the huge nurseCharting table, trims it down to take only the GCS scores</p>

<p>The <b>Joining all tables</b> file contains the merger code, for making the final training table.</p>

<p>Most of the larger datasets have been processed using a chunksize of 10000. This restricts memory usage and avoid memory overflow</p>


