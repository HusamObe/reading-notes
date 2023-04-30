# SQL lessons

## 1- SELECT queries
![](./assets/sql/sql%20select.png)
![](./assets/sql/sql%20REVIEW%20Select.png)
```
To retrieve data from a SQL database, we need to write SELECT statements.
```
----
## 2- using WHERE
![](./assets/sql/sql%20Queries%20with%20constraints.png)
```
In order to filter certain results from being returned, we need to use a WHERE clause in the query.
```
![](./assets/sql/sql%20Queries%20with%20constraints%202.png)
```
SQL supports a number of useful operators to do things like case-insensitive string comparison and wildcard pattern matching.
```
---

## 3- Filtering and sorting Query
![](./assets/sql/sql%20Filtering%20and%20sorting.png)
```
SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT.
```
```
SQL provides a way to sort your results by a given column in ascending or descending order using the ORDER BY clause.
```
```
The LIMIT will reduce the number of rows to return, and the optional OFFSET will specify where to begin counting the number rows from.
```
---
## 4- Multi-table queries with JOINs
![](./assets/sql/sql%20Multi-table%20queries%20with%20JOINs.png)
```
Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key.
```
```
The INNER JOIN is a process that matches rows from the first table and the second table which have the same key (as defined by the ON constraint) 
```
---
## 5- Inserting rows
![](./assets/sql/sql%20Inserting%20rows.png)
```
use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert.
```
```
each row of data you insert should contain values for every corresponding column in the table.
```
---
## 6- Updating rows
![](./assets/sql/sql%20Updating%20rows.png)
```
to update existing data use an UPDATE statement.
```
```
The statement works by taking multiple column/value pairs, and applying those changes to each and every row that satisfies the constraint in the WHERE clause.
```
---
## 7- Deleting rows
![](./assets/sql/sql%20Deleting%20rows.png)
```
to delete data from a table use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause.
```
```
always read your DELETE statements twice and execute once.
```
---
## 8- Creating tables
![](./assets/sql/sql%20Creating%20tables.png)
```
you can create a new database table using the CREATE TABLE statement.
```
```
If there already exists a table with the same name, the SQL implementation will usually throw an error, so to suppress the error and skip creating a table if one exists, you can use the IF NOT EXISTS clause.
```
---
## 9- Altering tables
![](./assets/sql/sql%20Altering%20tables.png)
```
to update your corresponding tables and database schemas use the ALTER TABLE statement to add, remove, or modify columns and table constraints.
```
```
you can even specify where to insert the new column using the FIRST or AFTER clauses.
```
---
## 9- Dropping tables
![](./assets/sql/sql%20Dropping%20tables.png)
```
you can use the DROP TABLE statement to remove an entire table including all of its data and metadata
```
```
the database may throw an error if the specified table does not exist, and to suppress that error, you can use the IF EXISTS clause.
```
