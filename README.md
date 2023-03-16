# Crowdfunding-ETL

## Purpose
Crowdfunding data is imported from an excel document and transformed into a relational database that follows principles of normalization. This project illustrates the overall ETL process and used a variety of tools to deal with common problems in unformatted data.

## Tools
Pandas is used to import data and split columns using a delimeter. Data types are changed, and new dataframes are created. Finally, regular expressions are used to extract and format data found in unformatted strings. New dataframes are exported as csv files. QuickDBD.com was utilized to create a database schema which was then executed in PostgreSQL.


## Results
From the notebook, four new csv files are created and exported to the 'Resources' folder. The script for the SQL database created is also included in the project as well as a database schema image. 
