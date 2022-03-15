# DBMS 

### Joins and its types: -
    A SQL Join statement is used to combine data or rows from two or more tables based on a common field between them. Different types of Joins are: 

- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN


## Definitions: -
### INNER JOIN:
    The INNER JOIN keyword selects all rows from both the tables as long as the condition satisfies. This keyword will create the result-set by combining all rows from both the tables where the condition satisfies i.e value of the common field will be same.


### LEFT JOIN: - 
    This join returns all the rows of the table on the left side of the join and matching rows for the table on the right side of join. The rows for which there is no matching row on right side, the result-set will contain null. LEFT JOIN
    is also known as LEFT OUTER JOIN.


### RIGHT JOIN: - 
    RIGHT JOIN is similar to LEFT JOIN. This join returns all the rows of the table on the right side of the join and matching rows for the table on the left side of join. The rows for which there is no matching row on left side, the result-set will contain null. RIGHT JOIN is also known as RIGHT OUTER JOIN.


### FULL JOIN: - 
    FULL JOIN creates the result-set by combining result of both LEFT JOIN and RIGHT JOIN. The result-set will contain all the rows from both the tables. The rows for which there is no matching, the result-set will contain NULL values.






### Normalisation: -
    Normalization is used to minimize the redundancy from a relation or set of relations. It is also used to eliminate the undesirable characteristics like Insertion, Update and Deletion Anomalies.

- 1NFA relation is in 1NF if it contains an atomic value. 

- 2NFA relation will be in 2NF if it is in 1NF and all non-key attributes are fully functional dependent on the primary key. 

- 3NFA relation will be in 3NF if it is in 2NF and no transition dependency exists. 

- 4NFA relation will be in 4NF if it is in Boyce Codd normal form and has no multi-valued dependency. 

- 5NFA relation is in 5NF if it is in 4NF and not contains any join dependency and joining should be lossless. 

## Atomic Value: -
    An atomic value is an instance of one of the built-in atomic data types that are defined by XML Schema. These data types include strings, integers, decimals, dates, and other atomic types. These types are described as atomic because they cannot be subdivided.

## Sql Introduction
    SQL is Structured Query Language, which is a programming language for storing, manipulating and retrieving data stored in a relational database. 

    SQL is the standard language for Relational Database System. All the Relational Database Management Systems (RDMS) like MySQL, MS Access, Oracle, Sybase, Informix, Postgres and SQL Server use SQL as their standard database language. 

### SQL Process
    When a SQL command is executed in any RDBMS, the system determines the best way to carry out your command and SQL engine figures out how to interpret the task. 

    Components like Query Dispatcher, Optimization Engines, Classic Query Engine, SQL Query Engine etc are involved in this process. 

    Note: A classic query engine handles all the non-SQL queries, but a SQL query engine won't handle logical files. 

## Sql Commands
    The standard SQL commands to interact with relational databases are CREATE, SELECT, INSERT, UPDATE, DELETE and DROP. These commands can be classified into the following groups based on their nature, 

- DDL - Data Definition Language
    DDL is short name of Data Definition Language, which deals with database schemas and descriptions, of how the data should reside in the database. 

    1. CREATE - create a new table, view for a table or other object in the database
    2. ALTER - modifies an existing database object, such as a table
    3. DROP - deletes an entire table, a view of a table or other objects in the database
    4. TRUNCATE - remove all records from a table, including all spaces allocated for the records are removed
    5. COMMENT - add comments to the data dictionary
    6. RENAME - rename an object

- DML - Data Manipulation Language
    DML is short name of Data Manipulation Language which deals with data manipulation and includes most common SQL statements such SELECT, INSERT, UPDATE, DELETE etc, and it is used to store, modify, retrieve, delete and update data in a database. 

    1. SELECT - retrieves records from one or more tables
    2. INSERT - creates a record
    3. UPDATE - modifies records
    4. DELETE - deletes records(one row or all rows)
    4. TRUNCATE - deletes records(all rows)
    4. DROP - deletes table with records(all rows)
    5. MERGE - UPSERT operation (insert or update)
    6. CALL - call a PL/SQL or Java subprogram
    7. EXPLAIN PLAN - interpretation of the data access path
    8. LOCK TABLE - concurrency control

- DCL - Data Control Language
    DCL is short name of Data Control Language which includes commands such as GRANT and mostly concerned with rights, permissions and other controls of the database system. 

    1. GRANT (Grant privilige(s) to user)
    2. REVOKE (Remove granted privilige(s) from a user)

- TCL - Transaction Control Language
    TCL is short name of Transaction Control Language which deals with a transaction within a database. 

    1. COMMIT - commits a transaction
    2. ROLLBACK - rollback a transaction in case of any error occurs
    3. SAVEPOINT - to rollback the transaction making points within groups
    4. SET TRANSACTION - specify characteristics of the transaction

_IMPORTANT SQL QUERIES_ 

### First highest salary : -
```sql
SELECT MAX(Salary) FROM Employee;
```

### Second Highest salary: -
```sql
SELECT MAX(Salary) FROM Employee WHERE Salary NOT IN (SELECT MAX(Salary) FROM employee);
```

### Join Query: -
```sql
SELECT * FROM Employee1 e1 *(INNER JOIN or OUTER JOIN or LEFT OUTER JOIN or RIGHT OUTER JOIN)* Employee2 e2 ON e1.id = e2.id;
```

### Delete query: -
```sql
DELETE * from TABLE_NAME where salary > 30000;
```

### Update query*
```sql
UPDATE TABLE_NAME SET salary = 25000 WHERE salary > 20000;
```

# To-do:
- [ ] Denormalization
- [ ] Triggers
- [ ] ACID property
- [ ] 1st, 2nd, 3rd...nth Highest salary
- [ ] DDL DML
- [ ] DBMS vs RDBMS
- [ ] difference between Delete, truncate, drop
- [ ] 1,2,3 tier architecture
- [ ] Group by, order by, having
- [ ] Queries related to joins
- [ ] They may show u few tables And ask u a query
- [ ] Print/remove duplicates In a table



## Special Thanks to: -
- [Praveen Yadav](https://www.linkedin.com/in/pixiedev)
- [Siddhartha Mishra](https://www.linkedin.com/in/sid0542)
