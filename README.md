# Movie-ETL-Module-8
# PROJECT OVERVIEW: 

This project focuses on the ETL (Extract, Transform and Load) process to clean data that will be used in analyzing Amazing Prime streaming algorithms. The process includes:
•	Extracting data from two different sources:
-	Wikipedia by filtering out all the TV shows, consolidating the redundant data, removing the duplicates, and formatting the. Data. 
-	Data rating from Kaggle website.
•	Transforming the data using Jupyter, Python and Pandas.
•	Loading the extracted data using PostgreSQL and pgAdmin to create a clean dataset. 


# ANALYSIS:

1.	"ETL_Function_test.ipynb": 
-	Data is extracted from the website in CSV and JSON formats. 
-	Data is transformed into Pandas data frames. 
-	With JSON, the file is loaded first and then transformed into a data frame. 

2.	“ETL_Clean_wiki_movies.ipynb”: 
-	Clean_movie function combines scattered data of alternative languages into one column alt_titles.
-	The change_column_name organizes column names into a consistent pattern. 
-	The function Extract_transform_load includes: python list comprehensions, apply() and map() methods with lambda functions and regular expressions. 

3.	“ETL_ clean_kaggle_data.ipynb”: 
-	The function Extract_transform_load provides new methods for cleaning Kaggle data. This includes filling null values, filtering unwanted columns, merging data frames using pd_merge method and changing datatypes. 

4.	“ETL_create_database.ipynb”:
-	Executed process using the extract_transform_load call. 

