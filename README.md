# project-2

**ETL - Extract, Transform and Load**

![This is an image](https://github.com/cjallow01/project-2/blob/main/ETL.PNG)

**Project Overview**

**Background**
Raw data exists in multiple places and forms. In order to perform any kind of data analysis, this data needs to be cleaned and structured. Data pipeline process ETL – Extract, Transform, and Load is a core concept in data engineering, ensuring that data is consistent, maintains its integrity, and nontheless strives for automatization of data wrangling. Without a consistent and robust data structure, it’s nearly impossible to perform any meaningful analysis.

Below is the wiki_movie_plots.CSV screenshot ![This is an image](https://github.com/cjallow01/project-2/blob/main/Wiki%20Screenshot.png)

Below is the imdb_top_1000.CSV screenshot ![This is an image](https://github.com/cjallow01/project-2/blob/main/IMDb%20Screen%20sh%20ot.png)

**Purpose**

The Netflico, a video streaming company, decided to sponsor an Intern program, where participants were trying to get an updated list of the Top 1000 movies so that the audience can get clear information of the movies. In order to provide organized and clean dataset, this project focuses on ETL* or Extract, Transform and Load process and includes the following:
•	Extracting data from two different sources.
o	The Internet Movie Database dataset from Kaggle
o	Wikipedia Movie Plots dataset from Kaggle
•	Transforming data using VSCode, Jupyter Notebook, Python, and Pandas 
•	Loading data using PostgreSQL and pgAdmin to host final cleaned data set.
Project Description
The goal of this analysis is to create automated pipeline that extracts, transform and loads data. The data is extracted from two sources, the first data set is Wikipedia Movie Plots csv on Kaggle https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots and the second data set is from IMDb Top 1000 Movies csv on Kaggle https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000. 
The following are the steps taken to achieve the result.

**Extract** 

The two sources of data is extracted from Kaggle in a csv format. The first data set is extracted from Wikipedia Movie Plots and the second data set is extracted from IMDb Top 1000 Movies. Below is a screenshot of both the dataset.

Here CSV files
 1. [imdb_top_1000.CSV](https://github.com/cjallow01/project-2/blob/main/imdb_top_1000.csv)
 2. [wiki_movies_plots.csv](https://github.com/cjallow01/project-2/blob/main/wiki_movie_plots(small%20file).xlsx)
 (note - the wiki_movie_plot CSV file is too large and couldn't be uploaed. We copied to top 500 rows to a new spreadsheet and uploaded.  

**Transform**

The data we clean from 25 columns to 16 columns and then merge into a single dataframe.

**Resources**

Data Sources:
•	Kaggle data from Kaggle.com - two files: movies_metadata.csv and ratings.csv

**Enviroment:**
•	PythonDataOne

**ETL Steps and process**

1.Dependencies
   -import requests
   -from config import api_key
   -import pandas as pd
  -import json
  -import os
  -from sqlalchemy import create_engine
  -import numpy as np
  -from pprint import pprint 
  -from sqlalchemy.orm import Session

2. Read the CSV files

3. Count/check duplicate in a DataFrame

4. Verify unwanted information/data before joining the tables

5. cleaning the data

6. Merging the tables to one dataset

7. dropping all un-needed column

8. Did the data load - create movies_merge_df dataset
