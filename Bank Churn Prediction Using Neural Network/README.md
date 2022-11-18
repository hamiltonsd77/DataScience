# Background and Context

Banks that provide financial services are concerned about customer turnover.  These businesses want to understand what influences a customer's decision to leave.

## Objective

Build a neural network based classifier that can determine whether they will leave or not in the next 6 months.

## Data Description

The case study is from an open-source dataset from Kaggle. The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, etc.

## Data Dictionary

* CustomerId: Unique ID which is assigned to each customer
* Surname: Last name of the customer
* CreditScore: It defines the credit history of the customer
* Geography: A customer’s location
* Gender: It defines the Gender of the customer
* Age: Age of the customer
* Tenure: Number of years for which the customer has been with the bank
* NumOfProducts: It refers to the number of products that a customer has purchased through the bank.
* Balance: Account balance
* HasCrCard: It is a categorical variable that decides whether the customer has a credit card or not.
* EstimatedSalary: Estimated salary 
* isActiveMember: Categorical variable describing whether the customer is an active member of the bank or not. 
* Exited: Categorical variable describing whether customer left the bank within six months or not:
                    0=No ( Customer did not leave the bank )
                    1=Yes ( Customer left the bank )
