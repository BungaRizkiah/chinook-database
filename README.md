# How to connect data from Chinook database into Python
Chinook Database is a SQLite sample database. Follow this link to download the sample database [Download Page](https://www.sqlitetutorial.net/sqlite-sample-database/). 
The database contains digital music store, including the tracks, artists, album title, and the transactions such as invoices and the customers. 

In this practice, we will talk about how to pull data from Chinook sample database into python and process the data for further analysis. 

# Files Included
- chinook_sql.ipynb
- chinook.cd
- README.md
- LICENSE

# Pulling data from SQL database into Python
To pull data from SQL database, the first step is to create connection. After creating connection, we will use pandas to read the SQL Query.  To write the query, you will need to first knows the list of tables in the database and the relationship diagram as shown in [this link](https://www.sqlitetutorial.net/sqlite-sample-database/).
