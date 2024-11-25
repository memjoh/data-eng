# Lego Database Creation for Analysis

work with [data from Lego](https://www.kaggle.com/datasets/rtatman/lego-database) containing *individual pieces > by color > by set/kit > grouped into larger themes* over time since 1950
* created a database, schemas and tables
* explored data and created views and datasets for analysis
* created explanatory visualizations

### Tech Stack Used
**PostgreSQL &nbsp;&nbsp; | &nbsp;&nbsp; pgAdmin &nbsp;&nbsp; | &nbsp;&nbsp; TablePlus &nbsp;&nbsp; | &nbsp;&nbsp; Hex &nbsp;&nbsp; | &nbsp;&nbsp; Tableau**  
<br />  

## 1 • Set Up Database
* Installed [PostgreSQL](https://www.postgresql.org/download/)
* Created new database and staging schema
* Imported [Initial Raw Data](https://www.kaggle.com/datasets/rtatman/lego-database) using SQL script to build tables
* Created new user with Select access to contents of the database
* Connected the database to TablePlus for later querying and analysis  

**Reference**  
[Local PostgreSQL Setup](https://www.youtube.com/watch?v=QPE5_p9PRsc)  
<br />    

## 2 • Create Schemas and Tables
[Schema Scripts](table_creation.sql)  
[Schema Diagram (ERD)](lego_er_diagram.png)  
<br />    

## 3 • Data Analysis
Questions asked:
* How many sets contain 'unique pieces' (pieces not used in any other set) and how has this changed over time?
* Are these 'unique pieces' more likely to be 'odd' colors?
* Have the colors and variety of colors changed over time?
<br />  

## 4 • Data Visualization
