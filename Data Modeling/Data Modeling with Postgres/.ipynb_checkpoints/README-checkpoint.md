<h3>Introduction</h3>

<p>A startup called Sparkify want to analyze the data they have been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to.</p>

<p>The aim is to create a Postgres Database Schema and ETL pipeline to optimize queries for song play analysis.</p>

<h3>Project Description</h3>

<p>In this project, I have to model data with Postgres and build and ETL pipeline using Python. On the database side, I have to define fact and dimension tables for a Star Schema for a specific focus. On the other hand, ETL pipeline would transfer data from files located in two local directories into these tables in Postgres using Python and SQL</p>

<h3>Schema for Song Play Analysis</h3>

<h3>Fact Table</h3>

<strong><em>songplays</em></strong> records in log data associated with song plays
<br>
<strong><em>Dimension</em></strong> Tables
<br>
<strong><em>users</em></strong> in the app
<br>
<strong><em>songs</em></strong> in music database
<br>
<strong><em>artists</em></strong> in music database
<br>
<strong><em>time:</em></strong> timestamps of records in songplays broken down into specific units

<h3>Project Design</h3>

<p>Database Design is very optimized because with a ew number of tables and doing specific join, we can get the most information and do analysis</p>

<p>ETL Design is also simplified have to read json files and parse accordingly to store the tables into specific columns and proper formatting<p>

<h3>Database Script</h3>

Writing "python create_tables.py" command in terminal, it is easier to create and recreate tables

<h3>Jupyter Notebook</h3>

<p>etl.ipynb, a Jupyter notebook is given for verifying each command and data as well and then using those statements and copying into etl.py and running it into terminal using "python etl.py" and then running test.ipynb to see whether data has been loaded in all the tables<p>

<h3>Relevant Files Provided</h3>

<p><strong><em>test.ipnb</em></strong> displays the first few rows of each table to let you check your database
<br>
<strong><em>create_tables.py</em></strong> drops and created your table
<br>
<strong><em>etl.ipynb</em></strong> read and processes a single file from song_data and log_data and loads into your tables in Jupyter notebook
<br>
<strong><em>etl.py</em></strong> run the full etl process
<br>
<strong><em>sql_queries.py</em></strong> containg all your sql queries and in imported into the last three files above </p>