﻿# Hospital_DB


How to Create Database without script using Postgres:
1)Log in to Postgres
2)Create the database hospital
3)Execute DataBase_PostgreSQL.sql to create tables and views for the database
4)Execute Dump_PostgreSQL.sql to publish data in the database

How to Create Database without script using MySQL:
1)Log in to MySQL
2)Create the database hospital
3)Execute DataBase_MySQL.sql to create tables and views for the database
4)Execute Dump_MySQL.sql to publish data in the database 

NOTE: Data contained in the dump file (which includes the INSERT statements) is not random, it is already prepared data to serve the purpose of the queries.


How to Run the python Script:
To use Postgres script you need:
Create the database hospital
Execute DataBase_PostgreSQL.sql to create tables and views
Download 'psycopg2' and 'names' python libraries
Open the Postgres script code and change the database name, user and password
Run the Data_Generator_PostgreSQL.py script

To use MySQL script you need:
Log in to MySql server and create the database hospital
Execute DataBase_MySQL.sql 
Download 'pymysql' and 'names' external libraries
Open the mysql script code and change the database name, user and password
Run Data_Generator_MySQL.py script



How to Run the GUI Application:
Requirements (Running JavaFx application)
After creating the database and filling it with the required data (i.e using the dump file or running the python script), follow the steps below in order to set up the GUI and execute required queries.
Check https://openjfx.io/openjfx-docs/#IDE-Intellij
In project settings, add library “org.postgresql:postgresql:42.2.52” using maven
Run application
You will be presented with a login interface to enter Database Name, user and password.
Click Connect and move to the Postgresql tab to execute the queries
