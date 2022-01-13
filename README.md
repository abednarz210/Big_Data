# Big Data


![BigData](https://www.atulhost.com/wp-content/uploads/2017/06/big-data-1536x864.jpg)


## Background

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can 
exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average 
local computer. The task will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The  second goal will be to use 
PySpark or SQL to perform a statistical analysis of selected data.

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.

## Task 

* Use the schema to create tables in your RDS database.
* Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook using S3 data sources. 
* Count the number of records (rows) in the dataset.
* Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.
* Load the DataFrames that correspond to tables into an RDS instance. 
