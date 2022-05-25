# AVIATION DATA WAREHOUSING


### OVERVIEW
The objective of this project is to build a Data Warehouse using airports, airlines, routes, and passenger datasets taken from various sources. The Data transformations will be done in the staging area and visualizations will be created using Tableau  to get some more general insights.

### DATASETS
The project has seven datasets that are taken from Flights.org and Kaggle. These datasets provide information about airports, airlines operated in different countries along with their respective IATA, ICAO codes, and routes between two airports. It also gives information on the number of passengers by different airlines.

### DATA WAREHOUSE CREATION SUMMARY USING AWS

1. First, We used S3 as the Staging area and created 2 buckets to store the original and transformed datasets.
2. Next, We performed Data cleaning and Transformations using AWSGlue Databrew.
3. After cleaning the data, We created Crawlers on the cleaned data using AWS Glue which was used as an ETL tool.
4. Last, We used Amazon Redshift as Data Warehouse and loaded the data from S3 to Redshift using AWS Glue.
5. We also connected Redshift with Tableau to create visualizations and get some insights on the data.


### CLOUD PLATFORM USED
1. AWS
