# **Movies-ETL**
Extract, Transform, Load

# Purpose

1) Created an ETL pipeline from raw data to a SQL database.
2) Extracted data from disparate sources using Python(jupyter notebbok).
3) Cleaned and transformed data using Pandas.
4) Used regular expressions (Regex) to parse data
5) Loaded data to PostgreSQL

The project included extracting a large data set from Kaggle and Wikipedia then transforming the data into a usable dataset for a hakethon. 

Once the data was transformed and narrowed in scope for the hackathon, the DataFrames were loaded into PostgresSQL.

# Results

The resulting database consists of two tables as shown below

A movies table with 6,052 rows of data, each representing a unique movie title. 
![movies_query](https://user-images.githubusercontent.com/96033163/155906985-fe266aef-98f5-4236-bc2d-8c2b2e4693ef.png)

A ratings table with 26,024,289 rows of data, each representing a viewer rating of 1-5. 
![ratings_query](https://user-images.githubusercontent.com/96033163/155906988-f5977ee3-118f-4fca-bc2d-235e3d0fe7e4.png)
