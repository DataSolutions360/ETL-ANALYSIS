# MOVIES ETL-ANALYSIS

## Overview ##

The purpose of this project was to create an automated pipeline that would cleanse, 
refine and categorize the data, eliminate unnecessary columns, and load the data into 
readable, usable tables.  Python coding was used in Jupyter Notebook and eventually 
will be added to a Postgres SQL Database.

## Results ##

## Deliverable 1: Write an ETL(Extract/Transform/Load) Function to read Three Data Files ##


Read 3 data files illustrated below:

### WIKI_MOVIES DataFrame: ###

wiki_movies_df.head()

![image](https://user-images.githubusercontent.com/8845050/171804802-4dfa60bc-6f07-4c1d-834b-92ecacfed630.png)

### KAGGLE_METADATA DataFrame: ###

kaggle_metadata_df.head()

![image](https://user-images.githubusercontent.com/8845050/171804673-07c8cb91-bcde-49b1-a088-9176e1f621d9.png)

### RATINGS DataFrame: ###

ratings.head()

![image](https://user-images.githubusercontent.com/8845050/171804578-2a7c7a1f-fd67-4b6d-9774-a3474a6fd0fe.png)

## Deliverable 2: Extract and Transform the Wikipedia Data ##

In Deliverable 2, the ETL process was placed on the Wikipedia Data file so it could be merged with the KAGGLE METADATA.  
A TRY-EXCEPT block was also implemented to catch all errors.

### wiki_movies_df (Deliverable 2) ###

![image](https://user-images.githubusercontent.com/8845050/172026241-5412d569-153e-45a1-ac4c-b7d8ed7eaf54.png)

### wiki_movies_df.column.to_list() ###

![image](https://user-images.githubusercontent.com/8845050/172026327-820520f0-da6f-497c-a0a2-ab7ae86b1bc1.png)

## Deliverable 3: Extract and Transform the Kaggle MetaData ##

Deliverable 3 consisted of the extraction and transformation of Keggle Matedata and MovieLens RATINGS data in order to convert the transformed data into seperate DataFrames.

Upon creating a Kaggle Metadata DF,  the Wiki_Movies_DF was with it to create a MOVIES_DF DataFrame.  The final step consisted of the merge of MovieLenss RATINGS data DF with Movies-DF to create the finished framework known as MOVIES_WITH_RATINGS_DF.

### Deliverable 3 Output ###

### movies_with_ratings_df ###

![image](https://user-images.githubusercontent.com/8845050/172026556-792fcc7d-705a-44ad-8c5d-82887aa42cde.png)

### movies_df ###

![image](https://user-images.githubusercontent.com/8845050/172026566-3f9c7401-c957-4ffc-aaa0-7ef127a3227a.png)

## Deliverable 4:  Create the Movie Database ##

The following 2 pictures illustrate the creation and import of data into their respective tables in Postgres DB environment
in the "movie_data" database:

### Movies Table ###

![movies_query](https://user-images.githubusercontent.com/8845050/172788612-268b854c-df1c-42be-b277-41c5952fe459.PNG)

### Ratings Table ###

![ratings](https://user-images.githubusercontent.com/8845050/172788671-443e3043-1ea9-4801-a69a-a1eed3e3a9f3.PNG)

