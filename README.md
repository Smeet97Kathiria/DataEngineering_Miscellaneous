These repository holds various code samples and sql scripts for different data engineering related work using python,sql,spark,AWS etc. 

# SQL_solutions
This Repository contains sql file which contains solutions to questions available on https://www.sql-practice.com/
In order to test the sql solution provided in the notebook, follow these steps:-
1) Go to this website -> website -> https://www.sql-practice.com/
2) Select hospitals.db on top left of the webpage if not automatically selected.
3) Select the appropriate question on top right section of the webpage for which you want to test the solution. 
4) After selecting the question paste in the solution and press the run button on top left. 

# Python,pySpark, SQL - Ecommerce Dataset EDA
The ecommerce EDA files contains an application which does exploratory data analysis on the Ecommerce dataset available here -> https://www.kaggle.com/datasets/carrie1/ecommerce-data 
The application was built using python.It creates a data operator class which performs Exploratory Data Analysis on the data using pyspark, SparkSQL,pandas. The application starts with loading the data file from local machine to hdfs which is then read using spark. Once the file is read in spark, it creates two temporary views invoices and items. These two views are then used to generate insights from the data. Visualization were created using matplotlib python library. 
