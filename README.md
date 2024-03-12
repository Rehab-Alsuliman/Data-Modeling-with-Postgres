### Project 1: Data Modeling with Postgres.

> in this project will do a database schema is designed to store song data, user data, artist data, time data, and songplay data. The ETL (Extract, Transform, Load) pipeline extracts data from JSON files, transforms it, and loads it into the appropriate tables in the database.


#### Scripts:

- sql_queries.py: in this script.
    > you will find here all sql queries ( I created five tables if dosent exist:
    tables:
        a- songplays table.
        b- users table.
        c- songs table.
        d- artists table.
        e- time table.
        
    **NOTE** --> run this script in etl.ipynb by start use this statement:
        ***we import the script "from sql_queries import *"***
        
- create_tables.py: here in this script 
    > I did connect to database and create a ***sparkifydb*** to start stoarge data on it.
    and I import it in etl.ipynb to prepare the environment to start work and take the sql_queries.py the direction where can create the five tables.

- etl.py here.
    >  here I did it to automates the process of extracting, transforming, and loading data into the Sparkify database, facilitating the  analysis and querying of music streaming data in etl.ipynb.
    

- etl.ipynb:
    >here serves as a guide for developing and understanding the ETL process before implementing it in the etl.py script, which automates the process for the entire dataset.
    

- test.ipynb
    > here serves as a tool for developers to validate their ETL process and database schema against common integrity issues before finalizing and submitting their project. 
    
    **NOTE**: just I did run here.
    

### run on these notebook "rtl.ipynb & run.ipynb".

 1- ***here in ETL.ipynb 1st: import create_tables i want to run the main function to start connect & create the database ![My Image](../images/import_main_fun_in_etl.png)***
 
 2- ***in this image I used the get_files function provided above to get a list of all song JSON. I select the first song in this list by use 0 index.the last statement I wanted to read the song file and view the data.![My Image](../images/read_and_select_data.png)***







