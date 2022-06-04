# MOVIES ETL-ANALYSIS

## Overview ##

The purpose of this project was to create an automated pipeline that would cleanse, 
refine and categorize the data, eliminate unnecessary columns, and load the data into 
readable, usable tables.  Python coding was used in Jupyter Notebook and eventually 
will be added to a Postgres SQL Database.

## Results ##

## Deliverable 1: Write an ETL(Extract/Transform/Load) Function to read Three Data Files ##


Read 3 data files illustrated below:

WIKI_MOVIES DataFrame:

wiki_movies_df.head()

![image](https://user-images.githubusercontent.com/8845050/171804802-4dfa60bc-6f07-4c1d-834b-92ecacfed630.png)

KAGGLE_METADATA DataFrame:

kaggle_metadata_df.head()

![image](https://user-images.githubusercontent.com/8845050/171804673-07c8cb91-bcde-49b1-a088-9176e1f621d9.png)

RATINGS DataFrame:

ratings.head()

![image](https://user-images.githubusercontent.com/8845050/171804578-2a7c7a1f-fd67-4b6d-9774-a3474a6fd0fe.png)

## Deliverable 2: Extract and Transform the Wikipedia Data ##

In Deliverable 2, the ETL process was placed on the Wikipedia Data file so it could be merged with the KAGGLE METADATA.  
A TRY-EXCEPT block was also implemented to catch all errors.

### wiki_movies_df (Deliverable 2) ###


