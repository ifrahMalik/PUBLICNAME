Welcome to the cab-project-1 wiki!

The database contains information pertaining to the number of fuel vehicles, electric vehicles, community profile data, and amount of emissions from fuel based passenger vehicles. The ddl.sql file contains the schema for each table in our database. By running the batch file EVGHG.sh, we create the database and the four tables needed. The four tables are based on the four relations from our schema: Electric_vehicles, GHG, Fuel_vehicles, Community_Prof. The attributes of the tables are taken from the relational schema from phase 3 of the collaborative project. The primary keys are set when creating a table for the database. In order to populate the tables with the data from our datasets, which are from Sustainable New Jersey's website, the excel datasets were transferred to csv files that contained the relevant data relating to our database tables. The column headers of the csv files for each dataset matched with the attributes of each table in the database. To transfer the data from the csv file to the tables we run the populate_tables.sh batch file. 
