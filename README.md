# plsql-allocation-
Project Overview
The project simulates a company’s bonus allocation system.
It includes:
•	A database schema for departments, employees, and bonuses
•	PL/SQL record types for employee and bonus data
•	Collections (associative arrays and nested tables) to store and process data in memory
•	A GOTO statement to skip certain employees (e.g., those on leave)
•	A stored procedure that calculates and stores employee bonuses
•	A report procedure to print bonus details
________________________________________
Database Objects
Object Type	Name	Description
Table	departments	Holds department information
Table	employees	Holds employee details
Table	bonuses	Stores computed bonuses
Package	bonus_pkg	Contains procedures for calculation and reporting
________________________________________
Key PL/SQL Features Used
Concept	Description
Record	Combines employee fields into a single variable
Associative Array	Groups employee records by department
Nested Table	Collects bonus results for later insertion
GOTO Statement	Used to skip employees who are on leave
________________________________________
How to Run the Project
Option 1 — Run Online (Recommended)
Use Oracle Live SQL:
1.	Log in or create a free Oracle account.
2.	Copy and paste the scripts from the sql/ folder in order:
o	01_create_schema.sql
o	02_insert_sample_data.sql
o	03_package_bonus.sql
o	04_run_tests.sql
3.	Execute each script.
4.	View the results in the Output tab.
Clone and Explore
git clone https://github.com/ub-victor/plsql-allocation.git
cd plsql-bonus-allocation

