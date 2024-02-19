# Hive Project to Build Data Warehouse for e-Commerce

# Project Overview
This project will focus on Apache Hive's capabilities to run analytical queries on huge datasets. We will use sales and customers data to perform the analysis and answer the following queries:
    - What is the sales contribution by the customer ?
    - What is the upper and lower discount limits offered by the products ?
    - Which age group of the customers contributes towards more sales ?

# Aim
This project aims to perform analytics on Sales and Customer data using Big Data tools such as Apache Sqoop, Apache Spark, Hive & HDFS

# Tech stacks used
 - SQL
 - AWS EC2
 - Docker
 - Sqoop
 - Hive
 - Spark
 - Scala

# Approach
 - Create an AWS EC2 instance and launch it
 - Create docker images using the docker-compose file on the EC2 machine
 - Create tables in MySQL
 - Load the data from MySql into HDFS using Sqoop commands
 - Move the data from HDFS to Hive
 - Extract customer information from data using Scala and store it as parquet file
 - Move the parquet file from Spark to Hive
 - Create tables in Hive and load the data from Parquet files into tables
 - Perform Hive analytics on Salea and Customer data

# Application Scope
 - Can be used to analyse and make informed data-driven decisions
 - when dealing with massive complex amount of datasets
 - To perform Parallel computations

# Application Flow
 - ![alt text](Hive-Project-to-build-Data-Warehouse-Solution.png)


    

