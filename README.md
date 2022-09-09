## Database Modelling with Cassandra

### Overview
In this project, the client have data collected from their app and want to analyze it. 
they've been collecting on songs and user activity on their new music streaming app.
The analytics team is particularly interested in understanding what songs users are listening to. 
Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.


### Project description
Based on the client requirments we'll create a Casandra database with tables designed to optimize queries on song play analysis.

the steps we follow stated below:
- Write an ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file.
- Model the data by creating tables in Apache Cassandra to run the required queries.
