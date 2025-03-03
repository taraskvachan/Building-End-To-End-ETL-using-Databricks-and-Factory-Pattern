# Building End-To-End ETL using Databricks and Factory-Pattern

## Project Description

In this project, we used DataBricks to create multiple ETL pipelines using the Python API of Apache Spark i.e. PySpark. We used sources like CSV, Parquet, and Delta Table then used Factory Pattern to create both reader and loader classes. Then we used PySpark DataFrame API and Spark SQL to write the business transformation logic. In the loader part, we have loaded data into two fashion one using DataLake and another by Data LakeHouse. 

## ETL Schema
![apple_analysis drawio](https://github.com/user-attachments/assets/08770f9d-c701-47b0-b367-f00471eabb05)

## Business logic
<ol>
<li>ETL 1: Customers who have bought Airpods after buying iPhone</li>
<li>ETL 2: Cuctomers who have bought both Airpods and iPhone</li>
</ol>
