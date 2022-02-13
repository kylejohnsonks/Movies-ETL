# Movies-ETL
 
# Purpose

The purpose of the Movies-ETL project is to extract movie data from three different sources, transform the data to reduce the number of columns, combine columns to produce more robust data sources and load the resulting data into Pandas DataFrames or tables in a sql database.

# Structure

The project requires four deliverable files:

1. ETL_function_test.ipynb
2. ETL_clean_wiki_movies.ipynb
3. ETL_clean_kaggle_data.ipynb
4. ETL_create_database.ipynb

### ETL_function_test.ipynb
In this file the basic form of the function to perform the ETL is established and tested.  It will extract data from three data files, one for each source, make transformations and return them as dataframes.

### ETL_clean_wiki_movies.ipynb
This file adds the clean_movie function to the solution before the movies are processed by the ETL function.

### ETL_clean_kaggle_data.ipynb
This file adds codes to clean various fields in the kaggle data before it is merged with the movie data to create the final dataframes.

### ETL_create_database.ipynb
This file modifies the solution from the previous three file to load that data into a sql database rather than pandas dataframes. 

#Tools used
- python, pandas
- Jupyter
- sqlalchemy
- RegEx