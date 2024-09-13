# Credit-Card-Churn
## Introduction

In today's competitive financial landscape, credit card companies face a formidable challenge in retaining their customer base. Customer churn, the phenomenon of customers discontinuing their relationship with a company, poses a significant threat to the profitability and sustainability of credit card businesses. Identifying customers who are at risk of churning and implementing targeted retention strategies is imperative for maintaining a loyal customer base and maximizing revenue.

To address this challenge, this project focuses on leveraging predictive analytics techniques to develop a robust model for credit card customer churn prediction

## Dataset 

The dataset used in this project contains information about banks and their existing and attrited customers. The target variable for prediction is the "Attrition Flag."

[Link to dataset](https://www.kaggle.com/datasets/manjuahuja/bank-churner?resource=download)

In this dataset there are several features that are used as parameters to make predictions, including:

1. CLIENTNUM: customer account number.
2. Attrition_Flag: customer status (Existing and Attrited).
3. Customer_Age: age of the customer.
4. Gender: gender of customer (M for male and F for female).
5. Dependent_count: number of dependents of customers.
6. Education_Level: customer education level (Uneducated, High School, 7. Graduate, College, Post-Graduate, Doctorate, and Unknown).
7. Marital_Status: customer's marital status (Single, Married, Divorced, and Unknown).
8. Income_Category: customer income interval category .
9. Card_Category: type of card used (Blue, Silver, Gold, and Platinum).
10. Months_on_Book: period of being a customer (in months).
11. Total_Relationship_Count: the number of products used by customers in the bank.
12. Months_Inactive_12_mon: period of inactivity for the last 12 months.
13. Contacts_Count_12_mon: the number of interactions between the bank and the customer in the last 12 months.
14. Credit_Limit: credit card transaction nominal limit in one period.
15. Total_Revolving_Bal: total funds used in one period.
16. Avg_Open_To_Buy: the difference between the credit limit set for the cardholder's account and the current balance.
17. Total_Amt_Chng_Q4_Q1: increase in customer transaction nominal between quarter 4 and quarter 1.
18. Total_Trans_Amt: total nominal transaction in the last 12 months.
19. Total_Trans_Ct: the number of transactions in the last 12 months.
20. Total_Ct_Chng_Q4_Q1: the number of customer transactions increased between quarter 4 and quarter 1.
21. Avg_Utilization_Ratio: percentage of credit card usage.


## Steps

This will be altered as the project is ongoing as it acts as a guide.

1. Perform data cleaning where i will check on any missing values,duplicated values,outliers etc
2. Apply several EDA techniques such as making use of visuals so as to gain more insight into the data set.
3. As our data set has 21 variables perform Principal component analysis to reduce its dimensionality.
4. Implement different machine learning models and compare on the basis of metrics like accuracy to find the best model.
