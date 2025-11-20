<h1>Churn Prediction Analysis</h1>


<h2>Description</h2>
In this project, I built a machine learning model to help a telecom operator predict customer churn and identify clients at risk of leaving. Using customer demographics, contract details, and service usage information, I explored the data, engineered features, and developed predictive models to support proactive retention strategies. This included analyzing subscription types, payment methods, and optional add-on services such as antivirus protection, cloud backup, tech support, and streaming.<br><br>


To build the churn prediction model, Interconnect’s marketing team collected data from multiple sources:

- contract.csv – contract details

- personal.csv – client demographics

- internet.csv – internet service information

- phone.csv – phone service information

Each dataset includes a unique customerID. Contract data is current as of February 1, 2020.
<br />


<h2>Languages and Utilities Used</h2>

- Python
- Pandas
- scikit-learn
- Machine Learning Libraries:
  - Logistic Regression
  - Gradient Boosting Classifier
  - XG Boost Classifier
  - Light Gradient Boosting Machine Classifier

<h2>Objective:</h2>
Predict whether a customer will churn, defined as:<br>
if end_date = "No" → Customer is active<br>
if end_date = a date → Customer has churned


<h2>Graphs:</h2>

<p align="center">
<b>Distributions - checking seasonal trends for new customer sign up<br/>
<img src="https://imgur.com/2TvHWqP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/eCX9lN7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<img src="https://imgur.com/t3NShys.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
