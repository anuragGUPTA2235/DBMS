# DBMS
## WHAT IS DATA?
Data is "01". Certainly! Data, in its raw form, represents isolated facts or observations without context or meaning. However, when data is structured, analyzed, and contextualized, it transitions into information, which holds significance and relevance for understanding, decision-making, and problem-solving. 
## WHY DATA IS THE NEW OIL?
Monetization: Similar to how oil was monetized through extraction, refining, and distribution, data can be monetized through various means such as targeted advertising, personalized services, and data analytics.
Meta sold users data to third party companies in billions
## DATABASE AND DATABASE MANAGEMENT SYSTEM?
A database is a structured collection of data organized in such a way that it can be easily accessed, managed, and updated. It typically consists of tables, each containing rows and columns representing individual records and attributes, respectively. Databases are used to store and retrieve data for various purposes, such as managing information about customers, products, transactions, and more.

A Database Management System (DBMS) is software designed to facilitate the creation, maintenance, and utilization of databases. It provides an interface for users to interact with the database, allowing them to perform tasks such as adding, modifying, and querying data. Additionally, a DBMS handles tasks such as data security, concurrency control (ensuring multiple users can access the database simultaneously without conflicts), backup and recovery, and optimization of queries for efficient data retrieval. Popular examples of DBMS include MySQL, Oracle Database, Microsoft SQL Server, PostgreSQL, and MongoDB.<br/>
![image](https://github.com/anuragGUPTA2235/DBMS/assets/161227082/856fd4b4-8623-41e8-80e4-af95270cb548)
![image](https://github.com/anuragGUPTA2235/DBMS/assets/161227082/382d36b6-57dc-451e-a212-1f3fe3fb61bb)
![image](https://github.com/anuragGUPTA2235/DBMS/assets/161227082/8454cc44-96a6-4a50-88eb-945eff22dd5b)
## WHY USE DATABASE, WE HAVE FILE SYSTEM? ADVANTAGES OF DBMS?
Data Integrity Enforcement: DBMSs enforce data integrity rules such as primary key constraints, foreign key constraints, and check constraints to ensure the accuracy and consistency of data. Filesystems lack built-in mechanisms for enforcing such constraints.
Transaction Management: DBMSs support transaction management to ensure data consistency and integrity even in the presence of concurrent access and system failures. Transactions in DBMSs follow the ACID properties (Atomicity, Consistency, Isolation, Durability), which filesystems do not inherently provide.
Concurrency Control: DBMSs implement concurrency control mechanisms to manage simultaneous access to data by multiple users or applications, preventing data corruption and maintaining consistency. Filesystems typically do not offer such mechanisms.
Data Security: DBMSs provide robust security features including user authentication, authorization, encryption, and auditing to protect sensitive data from unauthorized access, manipulation, or disclosure. Filesystems typically lack these advanced security features.
Query Optimization: DBMSs optimize query execution for improved performance by analyzing query plans, selecting appropriate indexes, and optimizing data access paths. Filesystems do not offer query optimization capabilities.
Indexing: DBMSs support indexing to enhance query performance by creating data structures that allow for fast retrieval of data based on specified criteria. Filesystems do not offer indexing capabilities for data stored within files.
Backup and Recovery: DBMSs provide mechanisms for backing up database data and restoring it in the event of data loss, corruption, or system failure. Filesystems may offer basic backup utilities, but they do not provide specialized backup and recovery features tailored for databases.
Data Modeling and Schema Management: DBMSs allow users to define and manage the structure of the database using data modeling techniques and schema management tools. Filesystems lack built-in support for structured data modeling and schema management.
## ABSTRACTION IN DATABASE MANAGEMENT SYSTEM
Abstraction in computer science refers to the concept of hiding complex details and showing only the essential features of an object or system. It's like using a remote control without knowing how it works inside, just knowing how to use it to change channels.<br/>
In the context of Database Management Systems (DBMS), abstraction refers to the process of hiding the complexities of the database system and presenting users with a simplified view or interface to interact with the database. There are typically three levels of abstraction in DBMS:<br/>
Sure, let's break down the three levels of abstraction in Database Management Systems (DBMS) in simpler terms:

### 1. Physical Level:

- What it deals with: This level deals with how data is physically stored on the storage devices (like hard drives).
- Details: It includes specifics like data file formats, storage structures (like tables or files), indexing methods (to optimize data retrieval), and how data is actually written and read from disk.
- Example: Imagine this level as understanding the details of how data is stored in a file on your computer's hard drive, including the format of each record and how the file is organized internally.

### 2. Logical Level:

- What it describes: The logical level describes what data is stored in the database and how it is related.
- Entities and Relationships: It defines entities (like tables in a relational database) and their attributes (like columns in a table), as well as the relationships between different entities.
- Example: Think of this level as the blueprint or design of a database, showing what tables exist, what each table contains, and how tables relate to each other (for example, which columns link one table to another).

### 3. View Level (or External Level):

- Closest to users: This is the level that users interact with directly, tailored to their specific needs.
- Customized Views: It provides customized views of the database, hiding certain details or showing data in a particular format that is useful for specific users or applications.
- Example: In practical terms, this could be a simplified interface or a specific report generated from the database that shows only the information relevant to a particular department or user role.

### Importance of these Levels:

- Data Independence: Each level provides a layer of abstraction, allowing changes in one level (like how data is physically stored) without affecting other levels (like how users view and interact with the data).
  
- **Simplicity and Security**: Abstraction helps in simplifying the complexity of managing data systems and enforcing security by controlling access to different levels of data.

In summary, these levels of abstraction in DBMS help in organizing and managing data efficiently while providing different perspectives and levels of detail to various users and applications.<br/>
![PPREPCS10](https://github.com/anuragGUPTA2235/DBMS/assets/161227082/daabc482-94b8-4882-b5aa-e81e9d77331d)

## WHAT IS INSTANCE
Instance is the collection of information stored in a database at any interval of time. It can differ at 1 pm and 2 pm on a production database.
## SQL SCHEMA (BLUEPRINT)
In the context of databases, a "database schema" (often shortened to "schema") refers to the structure or blueprint that defines the logical view of the entire database. It represents the organization of data in the database system, including the tables, fields, relationships, constraints, indexes, and other attributes that define how the data is stored and accessed.Sql schema dont frequently change while data inside it changes continuously.
## TYPES OF SCHEMA
### Physical Schema:

The physical schema defines how data is stored physically on a storage system such as disks. It includes details such as file organization, indexing methods, partitioning, and data storage formats. The physical schema is concerned with optimizing storage and retrieval efficiency.

### Logical Schema:

The logical schema defines the logical structure of the entire database, including tables, relationships, constraints, and permissions. It provides a conceptual view of the database and serves as a blueprint for creating the database. The logical schema is independent of the specific physical implementation details.
### External View schema
An external schema defines the views or subsets of the database that are accessible to specific users or applications. It hides certain details of the database schema and provides a tailored view of the data for different user groups or applications. External schemas help in achieving data independence and security.<br/>
Here also the schema are independent on each other, one change at one level dont affect other levels.GENERALLY, SCHEMA REFERS TO LOGICAL SCHEMA

### Conceptual Schema:
The conceptual schema represents the overall logical structure of the database from a business perspective. It defines entities, their attributes, and the relationships among them. The conceptual schema is often used during the initial design phase and provides a high-level view of the data requirements and relationships.
## MY OPINION
there are three levels in a database management system software, each level are independent of each other, changes in one dont affect others. suppose you want to split the partition of disk at physical level or add new partition, but it should not affect the logical level ie how tables are related to each other and also the views. the end user must not get disturbed. also if u change the logical schema, unless u want it should not affect the department views. by doing this we actually dont disturb the working of end users while we do important changes to our database.
### Data models
A data model is a way of structuring and organizing data in a database. It provides a blueprint for how data will be stored, accessed, and managed. Think of it as a framework or set of rules that define how information is represented and related to each other within a database system.

## Types -- 
#### Relational Model: 
The most widely used model, organizing data into tables with rows and columns. Relationships between tables are established using keys.<br/>

#### Entity-Relationship Model (ER Model):
Used for designing databases by representing entities (objects) and relationships between them graphically.<br/>

#### Object-Oriented Model:
Extends object-oriented programming concepts to databases, treating data as objects with attributes and methods.<br/>

#### Hierarchical Model:
Organizes data in a tree-like structure, suitable for representing parent-child relationships.<br/>

#### Network Model:
Similar to hierarchical but allows more complex relationships through pointers.<br/>

#### Document Model:
Stores semi-structured data as documents (e.g., JSON, XML), common in NoSQL databases.<br/>

#### Key-Value Model:
Simplest form, storing data as key-value pairs, efficient for quick access.<br/>

## DATABASE LANGUAGES
Data Definition Languages (DDL):

DDL is used to define the structure and schema of a database. Commands like CREATE, ALTER, and DROP are part of DDL and are used to create tables, modify table structures, and drop objects from the database.
Data Manipulation Languages (DML):

DML is used to manipulate data within the database. SQL's INSERT, UPDATE, DELETE statements are examples of DML commands that allow users to add, modify, and delete data from database tables.
Data Control Languages (DCL):

DCL is used to control access to data within the database. Commands like GRANT and REVOKE are part of DCL and are used to grant permissions to users and roles, and revoke those permissions when necessary.
Transaction Control Language (TCL):

TCL is used to manage transactions within the database. Commands like COMMIT and ROLLBACK are used to explicitly control the transactions and ensure data integrity.

## DATABASE AND APPLICATION COMMUNICATION
JDBC (Java Database Connectivity) and ODBC (Open Database Connectivity)(C C++)are both APIs (Application Programming Interfaces) designed to facilitate communication between applications and databases, but they serve different ecosystems and have distinct characteristics








