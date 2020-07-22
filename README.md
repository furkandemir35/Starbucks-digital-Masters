# STARBUCKS CAPSTONE PROJECT

### Installation <a name="installation"></a>
The most significant library for operating this project is the Python implementation of Anaconda Distribution. Install all the required packages for research and model building.
Make sure you have verison of python 3.x
Python libraries:
Pandas
Numpy
Matplotlib
Seaborn
Scikit learn

### Project Motivation <a name="project-motivation"></a>
This project is one part of my nanodegree program at Udacity. Main goal is to find best way to interact with customers over the Starbucks app.


### Data Preparation <a name="data-preparation"></a>
There are three datasets provided and each dataset is cleaned and preprocessed for further analysis. The target features for analysis are offer_success, percent_success.

1. Portfolio - renaming id column name to offer_id, one-hot encoding of channels and offer_type columns
2. Profile - profile: renaming id column name to customer_id, replacing age value 118 to nan, creating readable date format in became_member_on column, dropping rows with no gender, income, age data, converting gender values to numeric 0s and 1s, adding start year and start month columns (for further analysis)
3. Transcript - renaming person column name to customer_id, creating separate columns for amount and offer_id from value col, dropping transaction rows whose customer_id is not in profile:customer_id, converting time in hours to time in days, segregating offer and transaction data, finally dropping duplicates if any

### File Descriptions <a name="files"></a>
There is 3 type of the data for this project
1. portfolio.json - Data of offers
2. profile.json - Customer Data
3. transcript.json - Transactions

## Results<a name="results"></a>
Please check my blogpost on medium for the results:https://medium.com/@furkandemir35/starbucks-digital-masters-project-dc8e239db142
