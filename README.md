# RBC-Bank-Customer-Churn-Analysis

Overview

What is Customer churn? This is essentially the rate at which customers leave a business against the total customers that are actively in business. This is also known as churn rate or customer attrition.

Project Objective:

The objective of this analysis is to discover various factors contributing to increased customer churn rate at the bank, and provide the business users with these insights which they can use to make informed decisions and strategize on how to improve customer retention and reduce churn rate.

It is advantageous for banks to know what leads a client towards the decision to leave the company. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.

I used Power BI and Power Query for this analysis.

# About the data

The data used here is a fictional data which is in .csv and .xlsx format. Here is the list of column descriptions that are present in the dataset.

•	RowNumber—corresponds to the record (row) number and has no effect on the output.
•	CustomerId—contains random values and has no effect on customer leaving the bank.
•	Surname—the surname of a customer has no impact on their decision to leave the bank.
•	CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
Credit score:
•	Excellent: 800–850
•	Very Good: 740–799
•	Good: 670–739
•	Fair: 580–669
•	Poor: 300–579

•	Geography—a customer’s location can affect their decision to leave the bank.
•	Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.
•	Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
•	Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
o	Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
o	NumOfProducts—refers to the number of products that a customer has purchased through the bank. 
o	HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
•	1 represents credit card holder
•	0 represents non credit card holder
o	IsActiveMember—active customers are less likely to leave the bank.
•	1 represents Active Member
•	0 represents Inactive Member
o	Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
o	Exited—whether or not the customer left the bank.
  0 represents Retain 
  1 represents Exit
o	Bank DOJ — date when the Customer associated/joined  with the bank.

# Data Model

![image](https://github.com/user-attachments/assets/d51bdce0-7d6f-4586-9c7b-73a1310c4873)



