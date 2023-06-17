# Project-2
Bank Customer Churn Visualization and Prediction Model

## What is Churn for any business ?
* Churn rate, sometimes known as attrition rate, is the rate at which customers stop doing business with a company over a given period of time.
* Churn may also apply to the number of subscribers who cancel or don't renew a subscription. 
* The higher your churn rate, the more customers stop buying from your business.

## AIM OF PROJECT
* To predict whether a customer will leave the bank
* To know about the various reasons about why a customer would leave the bank
* To help the bank take various steps to preidentify customers who would want to leave so that they can focus on keeping them 
* Reduce churn


## DATA DESCRIPTION
#### Context
A dataset which contains customer data of a bank which includes data on whether they continue to stay with the bank or are leaving the bank.
#### DATASET COLUMNS

* RowNumber—corresponds to the record (row) number and has no effect on the output.
* CustomerId—contains random values and has no effect on customer leaving the bank.
* Surname—the surname of a customer has no impact on their decision to leave the bank.
* CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
* Geography—a customer’s location can affect their decision to leave the bank.
* Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
* Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
* Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
* Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
* NumOfProducts—refers to the number of products that a customer has purchased through the bank.
* HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
* IsActiveMember—active customers are less likely to leave the bank.
* EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
* Exited—whether or not the customer left the bank.
* Complain—customer has complaint or not.
* Satisfaction Score—Score provided by the customer for their complaint resolution.
* Card Type—type of card hold by the customer.
* Points Earned—the points earned by the customer for using credit card.

## This project shows:

* ability to write structured Python codes.
* bility to use existing libraries to process and analyze data.
* ability to use data pre-processing skills.
* ability to use exploratory analysis skills.
* ability to manupulate data.
* ability to build a ML model for churn prediction using various techniques and finding the best among them w.r.t accuracy
* ability to analyse a dataset and frame questions on why, when and how

#### LIBRARIES USED
* Pandas
* Numpy
* Matplotlib
* Sklearn
* Seaborn
* Imblearn
