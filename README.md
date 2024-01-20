# TotalSales_Prediction_LSTM
Total sales prediction using LSTM, 
THIS DATASET is IMPORTED from KAGGLE : https://www.kaggle.com/datasets/shedai/retail-data-set?resource=download&select=file_out2.csv

# About Dataset
Data holds the basic information about sales data. The company have sales agencies / resellers and branches and the data file holds only the branch/reseller information in the customer field.

Notes:
Please note that, for the privacy issues, the customerID, SKU and documentID is processed with LabelEncoder. So, each customer or each product has a unique ID in the data file.

Note 2: Data holds for more than 3 years, prices of the products can get raised by the time.

DocumentID : ID of the transaction. A transaction might hold multiple records for the same customer at the same date with multiple products (SKU). DocumentID might be useful for combining the transactions and detecting the items sold together.
Date : Date of transaction / sell. In the date time format.
SKU : Item / Product code. The unique code for each item sold.
Price : Sales price for the transaction. The price for the product for the customer for the date.
Discount : discount amount for the transaction.
Customer : Unique customer id for each customer. For the data set, customer can be a reseller or a branch of the company.
Quantity : Number of items sold in the transaction.

Version 2 Updates:
Newer version of the data set has more rows until 2023 January. Also some of the column names are updated for the naming standards in other Kaggle notebooks.

InvoiceID : ID of the transaction. A transaction might hold multiple records for the same customer at the same date with multiple products (SKU). DocumentID might be useful for combining the transactions and detecting the items sold together.
Date : Date of transaction / sell. In the date time format.
ProductID : Item / Product code. The unique code for each item sold.
TotalSales : Sales price for the transaction. If you want to get unit_price , divide TotalSales column to Quantity column
Discount : Discount amount for the transaction.
CustomerID : Unique customer id for each customer. For the data set, customer can be a reseller or a branch of the company.
Quantity : Number of items sold in the transaction.
