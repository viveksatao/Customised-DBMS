# Customised-DBMS
This project implements the DBMS for employee records.  We implement all SQL queries.  All data gets stored in Data structures.  Complete implementation is on Primary storage. 
This project implements a customized Database Management System (DBMS) for managing employee records using Java. It replicates basic SQL queries and stores data in primary memory (RAM) using LinkedList, allowing CRUD operations and aggregate functions without needing a traditional database.

#Features
CRUD Operations:

Insert new employee records
Display all records
Display specific records based on Employee ID or Name
Delete records based on Employee ID or Name
Aggregate Functions:

Calculate the sum of salaries
Find the maximum and minimum salary
Calculate the average salary
Count total employees
Utility Functions:

Display project information
Clean up resources using finalize() and System.gc()

#How It Works
Data Storage:
Utilizes LinkedList to store employee objects in memory.

User Interaction:
Provides a console-based menu for interacting with the DBMS.

Employee Management:
Each employee has a unique ID, name, address, and salary.
