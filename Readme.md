# MySql Documentation 
## What is SQL
- SQL is the standard language for dealing with Relational Databases.
- SQL is used to insert, search, update, and delete database records.
## Important Sql Commands 
- <a href="#" class="button danger"> **SELECT**</a>  extracts data from a database
- <a href="#" class="button danger"> **UPDATE**</a>  - updates data in a database
- <a href="#" class="button danger"> **DELETE**</a> - deletes data from a database
- <a href="#" class="button danger"> **INSERT INTO**</a> - inserts new data into a database
- <a href="#" class="button danger"> **CREATE DATABASE**</a> - creates a new database
- <a href="#" class="button danger"> **ALTER DATABASE**</a> - modifies a database
- <a href="#" class="button danger"> **CREATE TABLE**</a> - creates a new table
- <a href="#" class="button danger"> **ALTER TABLE**</a>- modifies a table
- <a href="#" class="button danger"> **DROP TABLE**</a> - deletes a table
- <a href="#" class="button danger"> **CREATE INDEX**</a> - creates an index (search key)
- <a href="#" class="button danger"> **DROP INDEX**</a>- deletes an index
<hr>
- <a href="https://github.com/GuruNadh552/MySql-Documentation/blob/main/Joins.md" class="button danger"> **CLICK Here** </a> - For Joins in Sql

## Select Statement :
- select * from tablename;
	- which will retrives all instances from the table tablename
- select column1,column2 from tablename;
	- which will used to retrieve the instances of the specific column from the table
- SElect Distinct column from the tablename;
	- it will retrive the instance without duplicates from the table
- Select count(DISTINCT column) from the table;
	- it will retrive the count of the instance without duplicates
------------------------------------------------------------------------------------------
## Where Statement :
which is used to filter the records in the database 

```
	Select * From table Where condition;
```

For checking multiple conditions we will use AND,OR,NOT;

```
Syntax :
	Select * from table where condition1 AND condition2;
	Select * from table where condition1 OR condition2;
	Select * from table where NOT condition1;
```
-------------------------------------------------------------------------------------------
## ORDER BY
which is used to sort the records based on the column in ascending (default) or descending order.

```
Syntax : 
	Select * from table ORder By (column1);
```

-------------------------------------------------------------------------------------------------
## Insert Into 
which is used to insert an instance to the table in the database

```
Syntax :
	Insert into table values("value1","value2");
```

--------------------------------------------------------------------------------------------------
## Update and Set
Which is used to update the values in the table based on the condition

```
Syntax:
	UPDATE table
	set column1 = value
	where column = "some";
```
---------------------------------------------------------------------------------------------------
## NULL value 
- checking whether the field contains a value or not

```
Syntax :
	Select * from table Where column_1 is null;
	Select * from table Where column_1 is NOT null;
```
--------------------------------------------------------------------------------------------------
## DELETE
	The DELETE statement is used to delete existing records in a table.
```
Syntax :
	DELETE from table where condition;
```
--------------------------------------------------------------------------------------------------
## MIN and MAX 
	To return the minimum and maximum value from the table 
```
Syntax :
	Select MIN(column1) as Minimum from table;
	Select MAX(column1) as MaximumValue from table;
```
--------------------------------------------------------------------------------------------------
## COUNT() , AVG() , SUM()
are the functions which will return the count , average and sum of the specific column in table

```
Syntax :
	Select COUNT(column) from table;
	Select AVG(column) from table;
	Select SUM(column) from table;
```
--------------------------------------------------------------------------------------------------
