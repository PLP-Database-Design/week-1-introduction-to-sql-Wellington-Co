1.State and Explain the components of a DBMS(Database Management System)

A Database Management System (DBMS) is a software system used to store, manage, and retrieve data. The main components of a DBMS are:

Database Engine: The core service that handles data storage, retrieval, and manipulation. It executes queries and ensures data is properly managed.
Database Schema: A blueprint or structure that defines how the database is organized, including tables, views, and relationships.
Query Processor: This component interprets and executes SQL queries sent by the user, ensuring they are processed efficiently.
Database Manager: Manages and controls access to the database, ensuring security, integrity, and consistency of data.
Transaction Management: Ensures that database transactions are processed reliably and supports operations like commit and rollback.
Security Management: Controls access permissions to ensure that only authorized users can view or modify data.

2.What is a relational database? Give 4 examples.

A relational database is a type of database that stores data in tables with rows and columns, where relationships between tables are established using keys (primary and foreign keys). Data in a relational database can be queried using SQL (Structured Query Language). Some examples of relational databases include:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server

3.State and Explain three classifications of SQL?
Data Query Language (DQL): This part of SQL is used for querying or retrieving data from a database. The most common DQL command is SELECT.
Data Definition Language (DDL): DDL is used to define and modify the structure of database objects like tables, indexes, and views. Common DDL commands include CREATE, ALTER, and DROP.
Data Manipulation Language (DML): DML is used to manipulate data in the database. It includes commands such as INSERT, UPDATE, and DELETE.

What is the difference between a Primary Key and a Foreign Key?
A Primary Key is a unique identifier for each record in a table. It ensures that every row in the table is unique and cannot be null. For example, a student ID in a student table is a primary key.

A Foreign Key is a field (or combination of fields) in a table that refers to the primary key in another table. It creates a link between two tables. For example, an order table might have a foreign key that links to the customer table by referencing the customer’s primary key.

What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities (objects) within a system and the relationships between them. It shows how tables in a database are connected. ERDs are used during the database design phase to help organize data structures and relationships clearly. Entities are represented by rectangles, and relationships are represented by diamonds or lines between them.

What are the advantages of relational databases?
Data Integrity: Relational databases ensure data consistency through constraints, like primary and foreign keys.
Flexibility: They allow easy querying and updates of data using SQL.
Scalability: Relational databases can handle large amounts of data efficiently.
Security: They offer robust security features to control user access and protect sensitive data.

State four types of data type used to store data in tables?
Integer: Used to store whole numbers (e.g., 1, 100, -45).
Varchar (Variable Character): Used to store text or strings with variable length (e.g., names, addresses).
Date/Time: Used to store dates and times (e.g., '2024-12-01', '14:30:00').
Decimal/Float: Used to store numbers with decimal points (e.g., 12.45, 3.1415).

What is the purpose of a database management system (DBMS)?
Purpose of a Database Management System (DBMS):

The primary purpose of a DBMS is to provide a systematic way to store, manage, and retrieve data in a structured form. It ensures data integrity, security, and efficient handling of large amounts of information. A DBMS also allows multiple users to access and modify data concurrently while maintaining consistency.