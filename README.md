# Python-Powered-Data-Extraction-and-MySQL-Connectivity

This repository has the code for the project which establishes a Database from extracted data.

Aim: Extract the data from Kaggle and set up a database on Azure Cloud Storage

Software Used: Python

Approach: 

Step 1: Extract the JSON formatted data from Kaggle, convert it to dataframes using pandas and upload the data to the Azure Cloud Storage.

Step 2: Link the python instance to Azure Cloud Storage. Update each column to the right datatypes.

Step 3: Find all the columns with multi-values attributes. Extract the multi-valued attribute into a table of it's own to increase readability, tag the new table with the parent table's key to maintain uniqueness.

Step 4: Link all the tables with right primary and foreign keys to establish a relationship among all the tables. 

Step 5: Establish a connection between the local MySql and Azure Cloud Database to query.

The repository has the code for extraction and data setup.

Additionally, there is another code file which shows how to query data without using sql rather using dataframes.
