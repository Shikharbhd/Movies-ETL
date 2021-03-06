# Movies-ETL

### Overview of the Project: 

The project aims to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables for Amazing Prime. The challenge will use refactored code from the ETL module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Project Deliverables: 

The challenge consists of four technical analysis deliverable as follows: 

a. Deliverable 1: Write an ETL Function to Read Three Data Files

b. Deliverable 2: Extract and Transform the Wikipedia Data

c. Deliverable 3: Extract and Transform the Kaggle Data

d. Deliverable 4: Create the Movie Database

e. Bonus Deliverable: A written report on the Movie Database analysis README.md.

### Resources:

Python PostgreSQL CSV Files:

  a. ratings.csv

  b. movies_metadata.csv

JSON Files:

  a. wikipedia-movies.json

### Results: 
The complete extract, transform, and load process resulted in database with two tables:

a. Movies Table consisting 31 columns and 6052 different movies.

![movies_query.png](https://github.com/Shikharbhd/Movies-ETL/blob/main/Resources/movies_query.png)


b. Ratings Table consisting 5 columns and over 26 million user ratings.

(![ratings_query.png](https://github.com/Shikharbhd/Movies-ETL/blob/main/Resources/ratings_query.png)
