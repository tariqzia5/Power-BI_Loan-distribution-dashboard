# Power-BI_Loan-distribution-dashboard
Understanding the problem statement and Import the dataset. This case is about a bank (Thera Bank). The majority of the customers are liability customers (depositors) with varying sizes of deposits.The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).
Dataset Download Link - https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling/download?datasetVersionNumber=1
Data Description
1. ID: Customer ID
2. Age: Customer's age in completed years.
3. Experience: Number of years of professional experience.
4. Income: Annual income of the customer ($000).
5. ZIPCode: Home Address ZIP code.
6. Family: Family size of the customer.
7. CCAvg: Avg. spending on credit cards per month ($000).
8. Education: Education Level of the customer. Here 1: Undergrad; 2: Graduate; 3: Advanced/Professional.
9. Mortgage: Value of house mortgage if any ($000).
10. Personal Loan: Did this customer accept the personal loan offered in the last campaign?
11. Securities Account: Does the customer have a securities account with the bank?
12. CD Account: Does the customer have a certificate of deposit (CD) account with the bank?
13. Online: Does the customer use internet banking facilities?
14. CreditCard: Does the customer uses a credit card issued by Universal Bank?
Transformation of the data:
Go to the home tab -> Click on transform data. This will open the power query editor.
For the variable Mortgage, a new flag variable is created that takes value 0 if the person has not taken a mortgage loan and value 1 if the person has taken a mortgage loan.
Go to Add column tab in the Power query editor -> Click on the custom column.

