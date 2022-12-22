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
 2. wiki_movies_plots.csv

**Transform**

There will be 16 columns 
Resources
Data Sources:
•	Wikipedia web scrape JSON file
•	Kaggle data from Kaggle.com - two files: movies_metadata.csv and ratings.csv
Enviroment:
•	PythonDataOne
Dependencies:
Software:
•	Jupyter Notebook
•	PostgreSQL and PgAdmin
References
•	(1) Module 8. Extractm Transform, Load, https://courses.bootcampspot.com/courses/200/pages/8-dot-1-1-extract-transform-load?module_item_id=73402, Trilogy Education Services, 2000, Web 6 Sept 2020.
Other Useful Articles
•	apply & map methods
•	List comprehension
•	More list comprehension
•	Lambda functions
•	RegEx
