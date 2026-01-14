# MySQL-Letterboxd-Library

Preqs: MySQL, a Letterboxd profile or in this instance mine.  

To download data from Letterboxd from your profile, go to your home page and select Edit profile:  
<img width="411" height="119" alt="image" src="https://github.com/user-attachments/assets/6ec5005b-ac11-4dbc-b056-e109b03662c5" />  
Then go the data tab and you will see account data with options to import or export your data, click on the export your data button.  
<img width="694" height="344" alt="image" src="https://github.com/user-attachments/assets/ad88f53c-f9e0-4b47-851e-20b11ef18712" />  
The files that are the most important would be watched.csv, ratings.csv, watchlist.csv.  
Then go create the following tables:  
<img width="572" height="687" alt="image" src="https://github.com/user-attachments/assets/0c172e3c-e9e0-4a3a-8623-cba7c529f917" />  
Then SHOW DATABAES like 'letterboxd%'; to verify.  
There are several ways to upload csv data to a MySQL Database, either SQL Command line, using the Table Data Import Wizard but I'll do the command line.  
Website to convert a csv file to a sql file: https://www.convertcsv.com/csv-to-sql.htm  
After downloading copy the text and paste it into the MySQL Query like so:  
<img width="714" height="499" alt="image" src="https://github.com/user-attachments/assets/1592fb0d-9ee4-4e1f-9f28-b9570076dd57" />  
And click the lightning button to run it.  
Then do the same for the others.  


