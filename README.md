# Pyspark_Hadoop_DataProcessing
This repository contains solutions for a PySpark and Hadoop assignment.  
The assignment demonstrates how to process different types of data using PySpark with HDFS and Hive.

The tasks include reading text, JSON, and CSV files, performing transformations, and storing results in formats like Parquet and ORC.

## Technologies Used

- PySpark
- Hadoop (HDFS)
- Hive
- Docker
- Python

## Questions Covered

### Q1 - Department Data Processing
Read a department text file from HDFS, create a new column called doubleSalary which is twice the salary, and store the result as a Parquet file.

### Q2 - JSON Data Filtering
Read a student JSON file and filter students who know Java but are not from the state OH. Display only firstname and gender.

### Q3 - Employee Data Processing
Read employee JSON data, remove duplicate records, store the result as ORC files partitioned by department, and calculate mean salary for each department.

### Q4 - Department Salary Aggregation
Join employee and department JSON files to calculate maximum salary and employee count for each department. Store the result in a Hive partitioned table using Parquet format.

### Q5 - Zipcodes Data Sampling
Read zipcode CSV data, generate a 50% sample dataset, create partitioned Parquet data based on State and City with a maximum of 3 records per file, and run a SQL query to filter specific states and cities.

## Data Files
 sample input files used in the assignment:

- Department.txt
- student.json
- employee.json
- employee2.json
- department2.json
- sample-zipcodes.csv
