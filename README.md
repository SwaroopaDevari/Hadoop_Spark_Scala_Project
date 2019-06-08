# Hadoop_Spark_Scala_Project

Hadoop Project:
Read data from local file system and HDFS(Hadoop distributed file system), then apply various transformations and load the file back to HDFS. (Reading and writing data to HDFS). All datasets are in the folder named Swaroopa. This involves working on various data formats like csv, parquet, avro, json for data validations and data cleansing.
Data is related to telecommunications domain from stores channel. ETL is performed using spark. Below  are two datasets (orders and orders_items) of textfiles.

Use Case 1: Using dataframes (spark 2.3.1, scala 2.11.8)
Using data frames find order items total cost, maximum order items cost, minimum order items cost and average order items cost for distinct order numbers per status per day (date should not have timestamp)

Use Case 2: Using Spark SQL
Use spark sql for usecase1(date should be ‘dd/MM’ format). 

Use Case 3: Using RDD and DataFrame
Using the below data for orders and orders_items, find total order items cost whose cost is greater than 7000.

Use Case 4: Using RDD and AggregateByKey
Using AggregateByKey  find max, min, avg and for distinct order numbers for “orders cos”. 

Use Case 5: Hive Analytical Aggregations: 
Analytical aggregations like sum,avg, ranking and windowing functions on orders.txt and order_items.txt dataset.

Use Case 6: Hive - Working on AVRO, creating avro schema, schema evolution.

Use Case 7: Using SBT tool: Scala Build Tool.

Use Case 8: Reading a semi structured data “JSON data” from HDFS and saving it as “Parquet and ORC” file formats.
