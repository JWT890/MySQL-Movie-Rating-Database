# MySQL-Letterboxd-Library

A MySQL database project that imports movie viewing, rating, and watchlist data from Letterboxd and uses SQL queries to analyze viewing history and rating trends.

Prerequisites  
MySQL  
A Letterboxd account/profile  
Letterboxd account data export  

For this project, I used my own Letterboxd profile and exported my account data.  

To download data from Letterboxd from your profile, go to your home page and select Edit profile:  
<img width="411" height="119" alt="image" src="https://github.com/user-attachments/assets/6ec5005b-ac11-4dbc-b056-e109b03662c5" />  
To download your account data from Letterboxd, first go to your Letterboxd profile and select Edit Profile.  
<img width="694" height="344" alt="image" src="https://github.com/user-attachments/assets/ad88f53c-f9e0-4b47-851e-20b11ef18712" />  
Next, select the Data tab. Under Account Data, Letterboxd provides options to import or export your account information. Select Export Your Data.  
Once the export is complete, several CSV files will be available. The files used for this project are:  
watched.csv — Movies that have been watched  
ratings.csv — Movies that have been rated  
watchlist.csv — Movies saved to the watchlist  

# MySQL Database Creation and Tables

After downloading the Letterboxd data, create the required MySQL database and tables.  
<img width="572" height="687" alt="image" src="https://github.com/user-attachments/assets/0c172e3c-e9e0-4a3a-8623-cba7c529f917" />  
After creating the database, verify that it exists by running:  

SHOW DATABASES LIKE 'letterboxd%';  

This confirms that the Letterboxd database was successfully created and is available for use.  

# Data import
There are several ways to import CSV data into MySQL, including:  

MySQL command line  
MySQL Table Data Import Wizard  
Converting the CSV data into SQL statements  
For this project, I used the MySQL command line approach.  
To convert the CSV files into SQL statements, I used ConvertCSV's CSV-to-SQL tool.  
After converting a CSV file, copy the generated SQL statements and paste them into the MySQL query window.  
<img width="714" height="499" alt="image" src="https://github.com/user-attachments/assets/1592fb0d-9ee4-4e1f-9f28-b9570076dd57" />  
Run the SQL statements using the lightning bolt button in MySQL.  
Repeat the process for the remaining CSV files:
watched.csv  
ratings.csv   
watchlist.csv  
Once the data has been imported, the database is ready for analysis.  

After importing the data, SQL queries can be used to verify the dataset and generate useful reports.  

# Average rating by decade
This query analyzes movie ratings by release decade to identify movie trends across different time periods.  
<img width="605" height="465" alt="image" src="https://github.com/user-attachments/assets/e16a809f-6dc7-42a3-92ff-0d32bdaec1d3" />  

# Most recent 10 viewings
This query identifies the ten most recently watched movies in the database.  
<img width="516" height="418" alt="image" src="https://github.com/user-attachments/assets/fb87dab6-b18c-4e77-89a1-a2ed5b09aff6" />  

# Average rating
This query calculates the overall average rating across the rated movies in the database.  
<img width="515" height="257" alt="image" src="https://github.com/user-attachments/assets/b6012070-2e6a-427e-a6c1-0100c2c9aa59" />  

# Top 23 rated films and shows
This query identifies the highest-rated films and shows in the dataset.  
<img width="520" height="569" alt="image" src="https://github.com/user-attachments/assets/e5aef3aa-da8a-4953-9bf1-4ec5c18ac31f" />  

# Lowest rated films
This query identifies the lowest-rated films in the dataset.  
<img width="585" height="499" alt="image" src="https://github.com/user-attachments/assets/4f9df1dd-4d7f-424b-adb1-8a8b0b916a53" />  

# Skills Demonstrated
MySQL  
SQL  
Relational Database Management  
Data Import and Organization  
Data Analysis  
Trend Analysis  
Reporting  
Data Validation  
Query Development  
CSV Data Processing  

# Project Overview
This project demonstrates the process of taking raw CSV data from an external source, importing it into a structured MySQL database, and using SQL queries to analyze the resulting dataset.

The project also demonstrates how structured data can be transformed into reports that provide insight into historical trends, rankings, and overall performance metrics.







