# Movies-ETL

## Challenge Overview:
The purpose of this challenge was to refactor the code from this module to create one function that takes in the three files (**Wikipedia data**, **Kaggle metadata**, **MovieLens rating data**) and performs the ETL (Extract, Transform, Load) process by adding the data to a PostgreSQL database.

This challenge consisted of the following four technical analysis deliverables:
- Deliverable 1: Write an ETL Function to Read Three Data Files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle data
- Deliverable 4: Create the Movie Database

## Results:
Below are the Jupyter Notebook result files for each deliverable as well as the additional requested outputs for deliverable 4:

- Deliverable 1
    - Jupyter Notebook results file: [ETL_function_test.ipynb](https://github.com/eldarias/Movies-ETL/blob/main/ETL_function_test.ipynb)
- Deliverable 2
    - Jupyter Notebook results file: [ETL_clean_wiki_movies.ipynb](https://github.com/eldarias/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
- Deliverable 3
    - Jupyter Notebook results file: [ETL_clean_kaggle_data.ipynb](https://github.com/eldarias/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
- Deliverable 4
    - Jupyter Notebook results file:[ETL_create_database.ipynb](https://github.com/eldarias/Movies-ETL/blob/main/ETL_create_database.ipynb)
    - **Movies** table total rows/records:
        - SQL Query: _SELECT COUNT(*) FROM movies_
        - <image src="./Resources/movies_query.png">
    - **Ratings** table total rows/records:
        - SQL Query: _SELECT COUNT(*) FROM ratings_
        - <image src="./Resources/ratings_query.png">