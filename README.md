# Amazon Vine Analysis. Project 16 of the UofT.
## `-Contents-`	
	
- [Overview of the Amazon Vine Analysis](#Overview-of-the-Amazon-Vine-Analysis)	
- [Resources](#resources)	
- [The Amazon Vine Analysis Result](#The-MechaCar-Statistical-Analysis-Result)
  - [ETL on Amazon Product Reviews](ETL-on-Amazon-Product-Reviews)
  - [Bias of Vine Reviews](Bias-of-Vine-Reviews)
- [The Amazon Vine Analysis Summary](#-The-Amazon-Vine-Analysis-Summary)
## `Overview of the Amazon Vine Analysis`	
	
The purpose for the the project is to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin by using PySpark. Also, to determine if there is any bias toward favorable reviews from Vine members in the dataset by using PySpark, Pandas, SQL.

The analysis consists the following: 
- Perform ETL on Amazon Product Reviews.
- Determine Bias of Vine Reviews.
- A Written Report on the Analysis.

## `Resources`	
The analysis is created using next software: Colaboratory (a hosted Jupyter notebook service), Visual Studio Code 1.58.0, PostgreSQL 11.12 and pgAdmin 5.5, AWS S3 and AWS RDS, Spark-3.0.3, Python 3.9.6, Pandas 1.2.4.

## `The Amazon Vine Analysis Result`
### `- ETL on Amazon Product Reviews`	

Using the cloud ETL process, it needs to create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets, and extract the dataset into a DataFrame. Next, transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.

The result of the ETL on Amazon Product Reviews can be found in the [Amazon_Reviews_ETL](./Amazon_Reviews_ETL.ipynb) file.

According to our results .

In addition, 
### `- Bias of Vine Reviews`

Using PySpark, Pandas, or SQL it needs to determine if there is any bias towards reviews that were written as part of the Vine program. Also, to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

The result of the Bias of Vine Reviews can be found in the [Bias of Vine Reviews](./Vine_Review_Analysis.ipynb) and [Bias of Vine Reviews Queries](./Vine_Review_Analysis.sql) files.

According to the 
## `The Amazon Vine Analysis Summary`	
- The total summary table shows below:

Additionally