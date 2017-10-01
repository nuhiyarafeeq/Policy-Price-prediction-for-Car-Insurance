Business Problem:

Using a customer’s shopping history, can you predict what policy they will end up choosing and the price for that policy?


About the Data : 

•	train.csv: quote history with multiple rows per customer Id. The last row shows the coverage option they ended up purchasing. 
•	train_short.csv: this data set is a subset of train.csv. It contains only the last rows for each customer ID. The rows that show which product is purchased by the customer. This file is created for the ones who do not wish to use the entire quote history while building their models. 
•	test_session_history.csv: shows the partial history of the quotes (2 sessions per customer) and do not have the purchased coverage options or the price. This data is optional and you do not have to use it for your predictions.
•	test.csv: there is one row per customer ID. You will notice that the last two columns in this data set are blank: policy and price. You are required to estimate these two values in the dataset for each customer ID. Policy can have values from 1, 2, 3 and 4, whereas price can have any integer values.    

