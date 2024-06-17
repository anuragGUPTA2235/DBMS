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
In the context of Database Management Systems (DBMS), abstraction refers to the process of hiding the complexities of the database system and presenting users with a simplified view or interface to interact with the database. There are typically three levels of abstraction in DBMS:




