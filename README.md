# Movies-ETL

## Purpose
In this repository are examples of the ETL process using real-life data files about movies: 
    - wikipedia_movies.json is a JSON file that gives information about movies from the Wikipedia website    
    - movies_metadata.csv is a csv file from the Kaggle website, also with information about movies
    - ratings.csv is a csv file from MovieLens. It is too large to import into Git Hub so this file has not been included.  It includes millions of consumer ratings collected from the website.

Using these files, I completed the following:
    - converted the JSON data to raw data and then to a Pandas DataFrame using a function
    - updated data in the tables to make them consistent for filtering and merging
    - filtered unnecessary data and rows with null values using list comprehension and regular expressions
    - merged tables to avoid duplicate data and provide a clean, comprehensive DataFrame of movie information
    - refactored file paths in the code to create an automated pipeline to take in new data and perform the same transformations
    - pushed the cleaned data to create 2 PostgreSQL tables in pgAdmin 

   

