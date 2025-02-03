# SQL
SQL is standard language for accessing and manipulating database.

### What is SQL ?
SQL stands for Structured Query Language
SQL lets you access and manipulate database

### Uses of SQL
* Execute queries against database
* Retreive data from database
* Insert records in database
* Update records in database
* Delete record from database
* Create a new database
* Create new tables in a database
* Create stored procedures in a database
* Create view in a database
* Set permissions on tables, procedures and views.

### Using SQL in your website
To build website that shows data from database, we will need :
* RDBS database program (SQL Server, MySQL)
* Server side scripting language like php, ASP etc
* Use SQL to get data you want
* HTML/CSS to style page.

### RDBMS (Relational Database Management System)
* RDBMS is basis for SQL
* Data in database is stored in database objects called tables.
* Tables is a collection related data enteries and it consists of column and rows
* Every table is broken into smaller entities called fields. this is nothing but column
* Record is also called row , is each individual entry that exists in a table
* Column is a vertical entity in a table that contains all information associated with specific field in a table

### SQL Statements
* Most action you need to perform on a database are done with SQL statments
* SQL statement, consists of keyword that are easy to understand

### Database Tables
* Database most often contains one or more tables.

### Note 
* SQL keywords are not case sensitive.
* SQL statement requires semicolon at the end of each SQL statement.

### Important SQL Commands
* **SELECT** :  Extract data from a database
* **UPDATE** : Updates data in a database
* **DELETE** : deletes data from database
* **INSERT INTO** : Insert new data into database
* **CREATE DATABASE** : Creates a new database
* **ALTER DATABASE** : Modifes a table
* **DROP TABLE** : Deletes a table
* **CREATE INDEX** : creates an index (search key)
* **DROP INDEX** : Deletes an index

### SQL Select Statement
* Select data from database
* Syntax
```
SELECT column1, column2, ... FROM table_name;
```
* Select ALL Columns : `SELECT * FROM Customers;`

### SQL SELECT DISTINCT Statement
* `SELECT DISTINCT` is used to return only distinct (different) values.
* Syntax
```
SELECT DISTINCT column1, column2, ... FROM table_name;
```
* Example : `SELECT DISTINCT Country FROM Customers;`

### Count Distinct
* DISTINCT keyword in a function called COUNT
* Syntax :
```
SELECT COUNT(DISTINCT Country) FROM Customers;
```

### SQL Where Clause
* WHERE clause  is used to filter records
* Syntax :
```
SELECT column1, column2, ... FROM table_name WHERE condition;
```

Note : WHERE clause is not only used in SELECT statements, it is also used in UPDATE, DELETE, etc.!

### Text Fields vs. Numeric Fields
* SQL requires single quotes around text values.
* Numeric value should not be enclosed in quotes.
   



