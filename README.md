***###Heading Sparkify: Data Modeling with Postgres***

***##Heading Introduction***

Sparkify is a startup company that wants to analyze the data they've been collecting on songs and user activity on their new music streaming app.

***##Heading Project Objective***

Define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.

***##HeadingContents***

***Data***

data/song_data: contains all files for song data
data/log_data: contains all files for log data

***Python files***

create_tables.py: Python file with functions to create and drop the database and its tables
sql_queries.py: Python file with drop, create, and insert SQL queries
etl.py: Python file that builds out the ETL process

***Jupyter Notebooks***

sql_queries.py: Contains all your sql queries, and is imported into the last three files above.
create_tables.py: Drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.

etl.ipynb: Reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.

etl.py: Reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.

test.ipynb: Displays the first few rows of each table to let you check your database.

ReadMe: Definition/Instruction file

Schema: Star Schema diagram


***##Must Have:***

Python 3, PostgresSQL, and/or Jupyter Notebook

***##Validation***

1. Run create_tables.py using terminal 
2. Run All cells in etl.ipynb
3. Run all cells in test.ipynb.
4. Run etl.py using terminal 
