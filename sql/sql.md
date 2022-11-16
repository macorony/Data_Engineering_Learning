# Day 1 Basic Concepts

**What is SQL?**
* SQL stands for structured query language.
* SQL let you acess and manipulate database

**What can SQL do?**
* execute queries on a database.
* retrieve data from a database.
* manipulate (insert, delete, update) records in a database.
* set permissions on tables, procedures, and view.

**Database tables**
* A collection of related data held in a table format within a database.
* It consists of columns and rows
* Tables rows and columns are referred to as records and fields
* Unique identifiers are used to identify records in a table and they are usually numbers

**Data types in SQL**
* String, a sequence of characters. In SQL *VARCHAR* is a popular string data type.
* *INT* for interger data type
* *NUMERIC* for float data type

**Schemas**
* A schemas records logical structures of data in a separate objects.
* Schemas may be assigned security permissions, making them an effective method for distinguishing and defending database based on user access priviledge.

**Basic commands**
* Create a table
    CREATE TABLE emp
       (EMPNO integer NOT NULL,
        ENAME VARCHAR(10),
        JOB VARCHAR(9),
        MGR integer,
        HIREDATE DATE,
        SAL integer,
        COMM integer,
        DEPTNO integer
        );

* Insert a table
    INSERT INTO EMP VALUES (7369, 'SMITH', 'CLERK', 7902, '1980-12-17', 800, NULL, 20);