# Market-Segmentation-on-Banking-Dataset-
### Objective :
For this particular casestudy, the task involves formulating customer segmentation to offer tailored recommendations, including savings plans, loans, wealth management, and other relevant services, to specific groups of customers.

![image](https://github.com/24lavprsingh/Market-Segmentation-on-Banking-Dataset-/assets/130772216/bd9e3ec1-ae8f-462d-b9c6-b1b1e3a00c40)


### Data Description :
The dataset provided contains information on the usage behavior of approximately 9000 active credit card holders over the past 6 months. The data is structured at a customer level and comprises 18 behavioral variables.

### Data :
Use the below link to download the Data Set:here

### Attribute Information :
The attribute information, or data dictionary, for the customer's credit card dataset is as follows:

### [Provide details of the attributes and their meanings here.]

CUSTID : Identification of Credit Card holder (Categorical)
<br>
BALANCE : Balance amount left in their account to make purchases
<br>
BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
<br>
PURCHASES : Amount of purchases made from account
<br>
ONEOFFPURCHASES : Maximum purchase amount done in one-go
<br>
INSTALLMENTSPURCHASES : Amount of purchase done in installment
<br>
CASHADVANCE : Cash in advance given by the user
<br>
PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
<br>
ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
<br>
PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
<br>
CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
<br>
CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
<br>
PURCHASESTRX : Numbe of purchase transactions made
<br>
CREDITLIMIT : Limit of Credit Card for user
<br>
PAYMENTS : Amount of Payment done by user
<br>
MINIMUM_PAYMENTS : Minimum amount of payments made by user
<br>
PRCFULLPAYMENT : Percent of full payment paid by user
<br>
TENURE : Tenure of credit card service for user

### FINAL FINDINGS 
### Cluster 1:

Customers in Cluster 1 have relatively high 'BALANCE,' 'PURCHASES,' 'ONEOFF_PURCHASES,' and 'CREDIT_LIMIT.'
<br>
They also have a moderate 'PURCHASES_FREQUENCY' and 'PURCHASES_TRX' (number of purchase transactions).
<br>
The 'CASH_ADVANCE' is moderate, indicating some cash advance usage.
<br>
This cluster represents customers who use their credit cards frequently for purchases, including both one-off and installment purchases, and tend to maintain a higher credit balance.

### Cluster 2:

Customers in Cluster 2 have similar mean values for most attributes to those in Cluster 1, but with slightly lower 'BALANCE' and 'CREDIT_LIMIT.'
<br>
They also show similar purchase behaviors with moderate 'PURCHASES_FREQUENCY' and 'PURCHASES_TRX.'
<br>
The 'CASH_ADVANCE' usage is again moderate.
<br>
This cluster represents customers who exhibit similar purchase behaviors to those in Cluster 1 but with slightly lower credit limits and balances.

### Cluster 3:

Customers in Cluster 3 have slightly lower 'BALANCE' and 'CREDIT_LIMIT' compared to both Cluster 1 and 2.
<br>
Their 'PURCHASES' and 'ONEOFF_PURCHASES' are higher compared to Cluster 2 but lower than Cluster 'PURCHASES_FREQUENCY' and 'PURCHASES_TRX' are moderate.
<br>
The 'CASH_ADVANCE' usage is similar to the other clusters.
<br>
This cluster represents customers with a more balanced purchase behavior, making moderate purchases and using their credit cards and cash advances more prudently.

​
