## SQL

SQL (Structured Query Language) a programming language for storing and processing information in a relational database.

It consists of:

* Keywords - Tell the database that we want to do something. Always written in capital letters e.g. `SELECT`, `CREATE TABLE`, `WHERE`

*  Identifiers - Tell the database what thing we want to act on. Always written in lower case letters e.g. `cities`, `users`, `customers`

### CREATE TABLE

The `CREATE TABLE` statement creates a new table in the database. It follows the structure:
```
CREATE TABLE table_name (
    column1 DATATYPE,
    column2 DATATYPE,
    column3 DATATYPE,
   ....
);
```
For example:
```
CREATE TABLE cars (
  brand VARCHAR(255),
  model VARCHAR(255),
  year INT
);
```