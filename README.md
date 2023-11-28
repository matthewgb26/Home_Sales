Home Sales Analysis with PySpark
Overview
This repository contains a Google Colab notebook for analyzing home sales data using PySpark. The notebook covers various tasks related to loading, exploring, and analyzing home sales data, as well as working with Parquet-formatted data.

Table of Contents
Prerequisites
Usage
Notebook Sections
License
Prerequisites
To run the notebook, you need:

Access to Google Colab or Jupyter Notebook environment.
An internet connection to access external data sources.
(Optional) A Google Drive account to save a copy of the notebook.
Usage
Open the notebook in Google Colab.
Make sure to run each cell in order to execute the code sequentially.
Follow the instructions and comments within the notebook for guidance.
Customize the notebook based on your specific requirements.
Notebook Sections
Setup:

Installs Spark, sets up Java, and initializes a SparkSession.
Data Loading:

Reads home sales data from an AWS S3 bucket.
Data Exploration:

Creates a temporary view and performs exploratory data analysis.
Spark SQL Queries:

Executes Spark SQL queries on the home sales data.

Query 1: Calculates the average price for four-bedroom houses sold each year.

Query 2: Determines the average price for three-bedroom, three-bathroom homes each year built.

Query 3: Calculates the average price for three-bedroom, three-bathroom homes with two floors, and at least 2,000 sqft each year built.

Query 4: Determines the view rating for the average price of homes above $350,000.

Caching:

Caches the temporary table for performance improvement.
Parquet Data:

Writes and reads data in Parquet format.
Analysis with Parquet Data:

Runs Spark SQL queries on the Parquet-formatted data.

Query 5: Filters out view ratings with an average price greater than or equal to $350,000.

Uncaching:

Uncaches the temporary table.
Additional Information:

Provides information about runtime measurements and comparisons.