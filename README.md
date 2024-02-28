## Fetch Rewards Coding Exercise

**First: Review Existing Unstructured Data and Diagram a New Structured Relational Data Model**

Refer to the file: ER_diagram.jpg

I have changed the names of '_id' field for Receipts, Users, and Brands schema to 'receipt_id', 'user_id' and 'brand_id' respectively.

**Second: Write a query that directly answers a predetermined question from a business stakeholder**

Refer to the file: SQL Queries.pdf

**Third: Evaluate Data Quality Issues in the Data Provided**

I have conducted Exploratory Data Analysis on Reciepts, Users and Brands data using Python jupyter notebook.

Major data quality issues found:

'Receipts' Data:

*Considerate amount of values missing in 'finishedDate', 'pointsEarned', 'purchasedItemCount', 'totalSpent', 'rewardsReceiptItemList' columns.
*Large number of outliers in values of 'pointsEarned', 'purchasedItemCount', 'totalSpent' columns. The distribution curves for values of these features is skewed. We do not know at this point whether these outliers are legit values or a result of some errors/inconsistency in processes that produce these values.

'Users' Data:

*More than half of the records are duplicate.

'Brands' Data:

*Considerate fraction of values missing for 'topBrand' and 'categoryCode' columns.

**Fourth: Communicate with Stakeholders**

Refer file: email.pdf
