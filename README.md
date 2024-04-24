# Snowflake_Practices
Project Context:
Customer Data warehouse – Need to store all the customer details and keep track the history as well. Create ETL Data Warehouse pipeline in snowflake to store customer history data.

1.	Day-1 load all the Data into Customer table.
2.	Next Day onwards, Identify the new customer and updated records based on existing Customer table data and insert new and update records with latest extract and load date.
3.	Get the All the customer latest details from customer table.
Data Set:
There is Customer Day-1 and Day-2 data set, in both files have customer details. Day-1 have all new records where Day-2 have new, update and duplicate records.




Contents:
Customer Day-1 and Day-2 File:
1.	ACCT_NO – Unique identifier key like Primary key. It holds Customer Account number.
2.	EXTRACT_DATE – Data Extract Date.
3.	NAME – Customer Name.
4.	ADDRESS – Customer Address.
5.	PHONE – Customer Phone number.
6.	EMAIL – Customer email id.
