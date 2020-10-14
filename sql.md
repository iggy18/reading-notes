## SQL

- SQL is a database computer language designed for the retrieval and management of data in a relational database.
- A relational database represents a collection of related (two-dimensional) tables.
- By learning SQL, the goal is to learn how to answer specific questions about this data.
- to retrieve data from a SQL database write a select statement
- `SELECT column, another_column,`
- `FROM mytable;`
- use an * to select all the data.
- In order to filter certain results from being returned, we need to use a WHERE clause in the query
- SELECT column, another_column, …
- `FROM mytable`
- `WHERE condition`
-    `AND/OR another_condition`
-    `AND/OR …;`
- `BETWEEN … AND …	Number is within range of two values (inclusive)`
- `NOT BETWEEN … AND …	Number is not within range of two values (inclusive)`
- `IN (…)	Number exists in a list`
- `NOT IN (…)	Number does not exist in a list`
- 
- SQL CREATE INDEX Statement
- `CREATE UNIQUE INDEX index_name`
- `ON table_name ( column1, column2,...columnN);`

-  The SQL Joins clause is used to combine records from two or more tables in a database. A JOIN is a means for combining fields from two tables by using values common to each.
- SQL is case sensitive
- All the SQL statements start with any of the keywords like SELECT, INSERT, UPDATE, DELETE, ALTER, DROP, CREATE, USE, SHOW and all the statements end with a semicolon (;).
- 