# SQL (Structured Query Language)

This is the language used to query and manipulate relational databases.

The sole responsibility of `SQL` is for performing database operations and not to build web or mobile applications. These databases are however used to power the web and mobile apps.

## Setting up an SQL Querying Environment

There are many ways of querying the database using `SQL`. The following list contains some of the platforms which can be used either offline or online.

    DBeaver
    MySQL Workbench
    pgAdmin
    phpMyAdmin
    Datagrip
    Navicat
    SQLite Studio
    SQL Server Management Studio (SSMS)

## Structure of an SQL Environment

There are many properties that are coupled together to form a stable SQL Environment.

### `Servers`: 
Servers in an SQL environment are either physical or virtual computers that are established to host one or more databases.
They are responsible for controlling db access, handling queries and enhancing database security and integrity.

### `Databases`: 
This is a structured collection of data organized for efficient retrieval, storage and manipulation. There are different types of databases:

    Relational: MySQL, PostgreSQL
    Non-Relational: MongoDB, Cassandra
    NewSQL: Google Spanner
Databases organizes data in a structured format to help users to easily perform the database operations.

### `Schemas`: 
A database schema defines the structure of the database and the relationship that exist between the data. Users can create multiple schemas to organize data that is related. 

### `Tables`: 
A table is a crucial unit of a database that organized the data in form of `rows` and `columns`.
It consist of columns which represents the attributes and rows which represents records. 

## SQL Data Types
SQL Data Types specify the type of data that can be stored in a column of a table. They define the operations that can be performed in the column and the data format. Choosing the right data type is essential for efficient data storage, data integrity and query performance.

#### Commonly used data types

### `INTEGER:`
Represents whole numbers and is used to represent numbers(numerical) without decimal places. 
Examples: `INT`, `BIGINT`, `SMALLINT`

### `DECIMAL/NUMERIC:`
Represents floating-point numbers with a specified precision and scale. Precision represents the number of digits, while scale represents the number of digits after the decimal points. <br />
Examples: `DECIMAL(p, s)`, `NUMERIC(p, s)`

