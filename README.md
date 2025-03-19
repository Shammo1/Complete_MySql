# Complete_MySql
## DATABASE
```sql
What is DataBase?
-> A database is a structured collection of data that`s stored electronically,it can include text,numbers,images,videos and files.
#Common type of Database :
->Centralized database.
->Cloud database.
->Commercial database.
->Distributed database.
->End-user database.
->Graph database.
->NoSQL database.
->Object-oriented database.
```

### DBMS (Database Management System):
```sql
DBMS is software that helps store, manage, and retrieve data from a database.
It provides a systematic way of organizing and maintaining data,
but it does not enforce relationships between data. Examples include file systems, XML, and JSON.
```
### RDBMS (Relational Database Management System):
```
RDBMS is an advanced type of DBMS that stores data in a structured format using tables (rows and columns).
It supports relationships between tables through primary and foreign keys and
follows ACID properties (Atomicity, Consistency, Isolation, Durability) to ensure data integrity.
Examples include MySQL, PostgreSQL, Oracle, and SQL Server.
```
```
+----------------------+---------------------+----------------------------+
|       Aspect         |        DBMS          |            RDBMS            |
+----------------------+---------------------+----------------------------+
| Data Structure       | Data stored as files | Data stored in tables       |
+----------------------+---------------------+----------------------------+
| Relationship Support | No relationships     | Supports relationships      |
+----------------------+---------------------+----------------------------+
| Data Integrity       | Low integrity        | High integrity with keys    |
+----------------------+---------------------+----------------------------+
```
## RDBMS
In a relational database, there are three main types of relationships between tables:
```
->One-to-One (1:1)
Each row in Table A is linked to one and only one row in Table B, and vice versa.
Example: A person and their passport information.
->One-to-Many (1:M)
Each row in Table A can be linked to multiple rows in Table B, but each row in Table B is linked to only one row in Table A.
Example: A customer and their multiple orders.
->Many-to-Many (M:M)
Multiple rows in Table A can be linked to multiple rows in Table B.
This relationship usually requires a junction table to link the two tables.
Example: Students and the courses they enroll in.
```
# MySql
 What is query? 
```
Query is a request or command sent to the database to perform specific operations like retrieving, inserting,
updating, or deleting data. Queries are written in SQL (Structured Query Language)
and are used to interact with the database.
```
 What is SQL?
```
SQL (Structured Query Language) is a standard programming language used to manage and manipulate relational databases. It is used to perform tasks such as querying data, inserting, updating, and deleting records, as well as creating and managing database structures like tables, indexes, and views.
```
