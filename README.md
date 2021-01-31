# Movies-ETL

## Overview

Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs my help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I plan on refactoring the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. The idea behind ETL is straightforward. Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. ETL breaks this problem into three steps, or phases: Extract, Transform, and Load. The ETL process for this project is as follows: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.

