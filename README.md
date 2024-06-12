# Credit-Card-Fraud-Detection

One of the most popular financial products for use in online payments and purchases is a credit card. Credit cards are a handy tool for managing your money, but they're not without risk. The unlawful use of another person's credit card or credit card details to make purchases or obtain cash is known as credit card fraud.

The dataset includes credit card transactions performed by cardholders throughout Europe in September 2013. This dataset shows the transactions that took place over a two-day period. Of the 284,807 transactions, 492 were fraudulent. Because of the extreme imbalance in the dataset, 0.172% of all transactions belong to the positive class (frauds).
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.




## Getting started

1. get the dataset 
[download the dataset](https://kh3-ls-storage.s3.us-east-1.amazonaws.com/Updated%20Project%20guide%20data%20set/creditcard-copy.csv)

2. install required python packages if previously not installed

3. Run list of code on Jupyter Notebook  as mentioned in CCf_v2.ipynb file 

