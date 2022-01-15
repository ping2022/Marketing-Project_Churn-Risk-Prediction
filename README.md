# Marketing Project_Churn Risk Prediction
Marketing Analysis Project


# Dataset
Kaggle: https://www.kaggle.com/parv619/hackerearth-how-not-to-lose-a-customer-in-10-days?select=train.csv


# Introduction
This Dataset belongs to a Machine Learning Challenge hosted at Hacker Earth.

Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period. Every user is assigned a prediction value that estimates their state of churn at any given time. It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.

The task is to predict the churn risk rate for a website based on the features provided in the dataset.

# Data description
Customerid: represents the unique identification number of a customer

Name: represents the name of a customer 

Age: represents the age of a customer

Securityno: represents a unique security number that is used to identify a person

Regioncategory: represents the region that a customer belongs to 

Membershipcategory: represents the category of the membership that a customer is using

Joiningdate: represents the date when a customer became a member 

Joinedthroughreferral: represents whether a customer joined using any referral code or ID 

Referralid: represents a referral ID

Preferredoffertypes: represents the type of offer that a customer prefers

Mediumofoperation: represents the medium of operation that a customer uses for transactions

Internetoption: represents the type of internet service a customer uses 

Lastvisittime: represents the last time a customer visited the website 

Dayssincelastlogin: represents the no. of days since a customer last logged into the website

Avgtimespent: represents the average time spent by a customer on the website

Avgtransactionvalue: represents the average transaction value of a customer

Avgfrequencylogindays: represents the no. of times a customer has logged in to the website 

Pointsinwallet Represents the points awarded to a customer on each transaction 

Usedspecialdiscount Represents whether a customer uses special discounts offered 

Offerapplicationpreference Represents whether a customer prefers offers

Pastcomplaint Represents whether a customer has raised any complaints

Complaintstatus Represents whether the complaints raised by a customer was resolved 

Feedback Represents the feedback provided by a customer 

Churnriskscore Represents the churn risk score that ranges from 1 to 5 Evaluation metric score = 100 x metrics.f1score(actual, predicted, average="macro")

# Approach
We have applied following machine learning algorithms with this dataset:
- Cluster analysis
- PCA
- Linear regression
- Binary Logistic Regression
- Multinomial Logistic Regression
- Ordinal Logistic Regression
