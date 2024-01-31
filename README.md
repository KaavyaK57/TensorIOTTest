# TensorIOTTest

The RatingAnalysis notebook in this repo is created for the following tasks
Data Assignment 1
·         Item having the least rating.

·         Item having most rating.

·         Item having the longest reviews.

·         Transform: change the date MM-DD-YYYY format.

·         Show a desired data frame operation which you learnt recently.

·         Convert the whole file into Parquet file after transforming.

Data Assignment 2
·       Save the data into a table (postgres/sql server)

Explanation

Cell 1 : Shows the libraries we need to run the notebook and other operations
Cell 2 : Creating SparkSession which helps us to connect to Spark
Cell 3 : Reading a file with million records which is in JSON format
Cell 4 : Just checking no.of records in the file
Cell 5 : Flattening Style column which has structured data into seperate columns 
Cell 6 : Giving proper names to column by removing : and space
Cell 7 : Renaming column asin to item_id just for reference and transforming review time in proper format of MM-DD-YYYY
Cell 8 : Calculating average rating for all items
Cell 9 : Checking item with least rating
Cell 10: Checking item with most rating
Cell 11: Calculation lenght of review text and getting maximum review lenght
Cell 12: Checking items with lengtiest reviews.
Cell 13: Writing file in parquet format in local path
Cell 14: Dataframe option that learnt recently.Persist to avoid Out Of Memory issues.
Cell 15: Writing data to SqlLite Server