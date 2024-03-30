# Tugas-GIT-Day-15

## Marketing Data ETL with Python

## Description:
This Python script implements a simple Extract, Transform, Load (ETL) process for marketing data. It reads a CSV file, cleans the data by removing missing values and reformatting dates, and then stores the transformed data in a new CSV file.

## Features:
1.  Reads CSV data using pandas
2.  Handles data cleaning (dropping rows with missing values)
3.  Converts dates to YYYY-MM-DD format
4.  Saves transformed data to a new CSV file

## Marketing Data ETL with Customer Segmentation (Python)

## Description:
This Python script provides an extensible Extract, Transform, Load (ETL) framework for marketing data. It builds upon a base MarketingDataETL class for general data processing and introduces a subclass, TargetedMarketingETL, to demonstrate customer segmentation based on purchase amount.

## Features:

### Base Class (MarketingDataETL):
1.   Reads CSV data using pandas
2.   Handles data cleaning (dropping rows with missing values)
3.   Converts dates to YYYY-MM-DD format
4.   Saves transformed data to a new CSV file

### Subclass (TargetedMarketingETL):
1.   Inherits all functionalities from MarketingDataETL
2.   Performs customer segmentation based on a specified criteria (amount spent in this example)
3.   Assigns membership ranks (Bronze, Silver, Gold, Platinum)
