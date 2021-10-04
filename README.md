## Movies-ETL (Module 8 Challenge)

## Overview 
Create an automated pipeline that takes in new data, perforsm the appropriate transformations, and loads the data into existing tables. We'd create a function in this module that will take three files as input - Wikipedia data, Kaggle metadata, and the MovieLens ratings data. We will then perform the ETL process and add data to a PostgreSql database.

### Deliverable-1 ###
#### ETL Function to Read Three Data Files ####

[Wikipedia Movies DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/wiki_movies_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/wiki_movies_df.png?raw=true)

[Kaggle Metadata DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/kaggle_metadata_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/kaggle_metadata_df.png?raw=true)

[Ratings DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_df.png?raw=true)

### Deliverable-2 ###
#### Extract and Transform the Wikipedia Data ####

[Transformed Wikipedia Movies DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D2_wiki_movies_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D2_wiki_movies_df.png?raw=true)

[Transformed Wikipedia DataFrame Columns](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D2_wiki_movies_df_columns.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D2_wiki_movies_df_columns.png?raw=true)


### Deliverable-3 ###
#### Extract and Transform the Kaggle Data ####

[Transformed Movies with Ratings DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_wiki_ratings.df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_wiki_ratings.df.png?raw=true)

[Transformed Movies DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_movies_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_movies_df.png?raw=true)

[Transformed Wikipedia Movies DataFrame](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_wiki_movies_df.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/D3_wiki_movies_df.png?raw=true)

### Deliverable-4 ###
#### Create the Movie Database ####

[No. of Records loaded into Movies Table in PostgreSQL](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/movies_query.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/movies_query.png?raw=true)

[No. of Records loaded into Ratings Table in PostgreSQL](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_query.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_query.png?raw=true)

[Ratings upload Time elapsed](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_upload_time_elapsed.png)
![](https://github.com/neerajain9/Challange-8-Movies-ETL/blob/Data-Science/Resources/ratings_upload_time_elapsed.png?raw=true)