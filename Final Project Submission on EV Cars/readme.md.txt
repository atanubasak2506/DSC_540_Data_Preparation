
=============================================================
=============================================================

            Project: Project on EV Cars

=============================================================
=============================================================
In this data visualization project, I did the visual analysis on the Battery Electric
Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered through Washington
State Department of Licensing (DOL). Getting complete data for the project was quite hard, so I
had to collect it from various sources, I wanted to present the EV level analysis in respect to
users, so I created some user data and added it to the analysis.

=============================================================
Data Collection
=============================================================
I have chosen 3 types of sources for data collection, one of with is for EV Car
data, the next one is an API bases side which I have used to create random users for the EV. The
third and last one is the web-based data, where I have taken a site that keeps the cost of living
for different state, I have replaced the states using the random city from the EV car data,
Because the complete data for EV belong to only one state i.e., Washington State
=============================================================
Feature Engineering and Data Store
=============================================================
This part is one the major states, where I have created
several derived fields based on the actual fields for the analysis purpose. I have stored the data
in SQL database for future availability. I pulled the derived data after feature engineering and
did a SQL joining to create a master table where I have joined the 3 dataset EV Car Info, EV
Users and Cost of living data.
=============================================================
Ethical Implication
=============================================================
As EV car data analysis has user level data, we must be sensitive while
dealing with and publishing this information. This data also has email addresses tagged with
name and city, which is Personal identifier or PII data.

=============================================================
Software Requited
=============================================================

Python
Jupyter Notebook


=============================================================
Prerequisite
=============================================================

pip install pandas
pip install numpy
pip install seaborn
pip install sqlite3


=============================================================
Contact
=============================================================

Atanu Basak
atanucoolb@gmail.com


