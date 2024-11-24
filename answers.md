# SQL Assignment Week 1 Answers

---

### 1. **State and Explain the components of a DBMS (Database Management System)**

A **Database Management System (DBMS)** is a software system used to store, manage, and manipulate data. The main components of a DBMS are:

- **DBMS Engine**: The core service that handles the storage, retrieval, and manipulation of data in the database.
- **Database Schema**: Defines the logical structure of the data, including the relationships between tables, views, and other objects.
- **Query Processor**: Responsible for interpreting and executing SQL queries, optimizing query performance, and ensuring data consistency.
- **Database Manager**: Manages the interactions between the DBMS and the operating system, including memory management, caching, and file handling.
- **Transaction Management**: Ensures that all database transactions are processed reliably and supports ACID (Atomicity, Consistency, Isolation, Durability) properties.
- **Data Dictionary**: Stores metadata about the database, such as information about tables, columns, constraints, and relationships.
- **Security Management**: Manages access control and ensures the integrity and confidentiality of data by enforcing user permissions and authentication.

---

### 2. **What is a relational database? Give 4 examples.**

A **relational database** is a type of database that stores data in tables (also called relations), with rows representing records and columns representing attributes. These databases use structured query language (SQL) to manage and manipulate data, and they rely on relationships between tables to ensure data consistency and integrity.

Examples of relational databases:
1. **MySQL**
2. **PostgreSQL**
3. **Oracle Database**
4. **Microsoft SQL Server**

---

### 3. **State and Explain three classifications of SQL**

SQL (Structured Query Language) is classified into three main categories based on functionality:

- **Data Definition Language (DDL)**: Used to define and modify database structures such as tables, indexes, and schemas. Common DDL commands include:
  - `CREATE` (creates new database objects)
  - `ALTER` (modifies existing database objects)
  - `DROP` (removes database objects)

- **Data Manipulation Language (DML)**: Deals with the manipulation of data within the database. DML commands include:
  - `SELECT` (retrieves data)
  - `INSERT` (adds data)
  - `UPDATE` (modifies data)
  - `DELETE` (removes data)

- **Data Control Language (DCL)**: Controls access to data within the database. DCL commands include:
  - `GRANT` (gives users permission to access database resources)
  - `REVOKE` (removes permissions from users)

---

### 4. **What is the difference between a Primary Key and a Foreign Key?**

- **Primary Key**: A primary key is a column (or a set of columns) in a table that uniquely identifies each row in the table. It must contain unique values and cannot contain NULL values.
  
  Example: In a `Users` table, the `user_id` column could be the primary key because each user has a unique identifier.

- **Foreign Key**: A foreign key is a column (or set of columns) in a table that establishes a link between the data in two tables. It points to the primary key in another table, enforcing referential integrity between the two tables.
  
  Example: In an `Orders` table, the `user_id` column might be a foreign key referencing the `user_id` in the `Users` table.

---

### 5. **What is an Entity-Relationship Diagram?**

An **Entity-Relationship (ER) Diagram** is a visual representation of the structure of a database. It shows the entities (tables) in the database and the relationships between them. Each entity is represented as a rectangle, and the relationships between entities are represented as diamonds or lines. ER diagrams are used during the design phase of a database to ensure a clear understanding of the data and its relationships.

Key components of an ER diagram include:
- **Entities**: Represent tables or objects that hold data.
- **Attributes**: Properties of entities, represented by ovals connected to entities.
- **Relationships**: Associations between entities, represented by diamonds or lines.
- **Primary Keys**: Uniquely identify records in an entity, often denoted by underlining.

---

### 6. **What are the advantages of relational databases?**

Some advantages of relational databases include:

1. **Data Integrity**: The use of constraints like primary keys and foreign keys ensures that data is accurate and consistent.
2. **Flexibility**: Tables can be easily modified, and new tables can be added without disrupting the existing structure.
3. **Data Security**: Relational databases provide robust security features, allowing control over who can access or modify data.
4. **Scalability**: They can efficiently handle large amounts of data, making them suitable for both small and large-scale applications.
5. **Query Capabilities**: SQL provides powerful and flexible tools for querying and manipulating data.

---

### 7. **State four types of data type used to store data in tables**

Here are four commonly used data types in relational databases:

1. **VARCHAR (Variable-length Character)**: Used to store text or string data of variable length.
2. **INT (Integer)**: Used to store whole numbers.
3. **DATE**: Used to store date values (e.g., `YYYY-MM-DD`).
4. **DECIMAL (or NUMERIC)**: Used to store exact numeric values with a fixed number of decimal places.

---

### 8. **What is the purpose of a database management system (DBMS)?**

The primary purpose of a **DBMS** is to provide a systematic way to manage and manipulate data efficiently. A DBMS allows users and applications to store, retrieve, and modify data, ensuring data integrity, security, and consistency. It abstracts the underlying data storage, making it easier for users to interact with the data through SQL queries.

Key purposes include:
- **Data Storage Management**: Efficiently stores data on disk and in memory.
- **Data Retrieval**: Provides mechanisms to retrieve data in a fast and efficient manner.
- **Data Integrity**: Ensures the accuracy and consistency of the data.
- **Concurrency Control**: Manages multiple users accessing the database simultaneously.
- **Security**: Protects data from unauthorized access.
- **Backup and Recovery**: Ensures data can be recovered in case of failure.

---

