# ETL-Pipeline-Project-Spar-Nord-Bank

Our primary responsibility in this project is to develop a batch ETL pipeline that will extract transactional data from RDS, transform the data as needed, and load it into the appropriate dimensions and facts within the Redshift Data Mart (Schema).

We have data from more than 100 ATMs across Denmark. Data is captured for every transaction including, card type, location, date, time, ATM type, etc. Spar Nord Bank is trying to observe the withdrawal behavior and the corresponding dependent factors to optimally manage the refill frequency. Apart from this, other insights also have to be drawn from the data. Also, the transaction amount field in the data set was added separately using a random function for the analysis purpose.

Technology used:-Used Sqoop to ingest data from RDS to HDFS, PySpark to transform and load data to S3, and Redshift to create and query dimension & fact tables.
