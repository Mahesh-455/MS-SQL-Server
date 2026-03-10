**SSIS CSV to SQL Server ETL Project**

This repository contains a simple ETL pipeline built using SQL Server Integration Services (SSIS) to load raw CSV data into a SQL Server database.
The project demonstrates how structured data can be extracted from a flat file, transformed if necessary, and loaded into a relational database table.

**Project Overview**

The SSIS package performs the following operations:
1. Reads raw data from a CSV file
2. Uses a Flat File Connection Manager to parse the file
3. Loads the data into a SQL Server table
4. Enables structured data storage for reporting and analytics

This project demonstrates a basic Extract–Transform–Load (ETL) workflow using SSIS.

**Technologies Used**

1. Microsoft Visual Studio 2026 Community Edition
2. SQL Server 2022 Developer Edition
3. SQL Server Integration Services (SSIS)
4. SQL Server Management Studio (SSMS)

**ETL Workflow**

The ETL pipeline follows this process:
CSV File
↓
SSIS Data Flow Task
↓
Flat File Source
↓
(Optional Transformations)
↓
OLE DB Destination
↓
SQL Server Table

**Project Structure**

When the SSIS solution is created in Visual Studio, the following files and folders are generated:
1. .sln → Solution file
2. .dtproj → SSIS project file
3. /SSIS Packages/ → ETL packages (.dtsx files)
4. /Connection Managers/ → Database and file connections
5. /Parameters/ → Project-level parameters
6. /bin/ → Build output files
7. /obj/ → Temporary build files


**Solution Explorer View**

Below is the SSIS project structure as seen in Visual Studio.

<img width="1917" height="755" alt="image" src="https://github.com/user-attachments/assets/9628a42c-30ef-4e1a-852b-c7d698f76775" />

**Flat File Source Configuration**

The raw CSV file is configured using a Flat File Connection Manager which defines:
1. File location
2. Column delimiters
3. Data types
4. Column names

<img width="915" height="688" alt="image" src="https://github.com/user-attachments/assets/e068a246-e435-46e7-9750-5be6ab0bc457" />

**Data Flow Task**

The Data Flow Task reads the CSV file and transfers the data to SQL Server using an OLE DB destination.

<img width="1012" height="810" alt="image" src="https://github.com/user-attachments/assets/ad92a7d8-d73b-4360-8b3d-51ed9a355079" />

**Destination Table in SQL Server**

The processed data is loaded into a SQL Server table, which can be viewed using SQL Server Management Studio (SSMS).

<img width="1070" height="499" alt="image" src="https://github.com/user-attachments/assets/f70232ef-8a02-4630-9deb-eddd64fd1146" />

<img width="1063" height="786" alt="image" src="https://github.com/user-attachments/assets/97a9b118-40df-4811-9b69-d2a8fc1f0603" />

**Dependent files created for this project**

<img width="801" height="385" alt="image" src="https://github.com/user-attachments/assets/b79c01a8-8505-49a8-8216-9a91dbc4bb8b" />


**Querying the Loaded Data**

Once the data is loaded, it can be queried using SQL.

<img width="1341" height="772" alt="image" src="https://github.com/user-attachments/assets/a1606750-56d2-41f7-8af9-eb0035877d90" />

**Use Cases**

This project demonstrates a common data engineering scenario:
1. Loading raw files into a database
2. Data ingestion pipelines
3. Batch data processing
4. Preparing data for BI tools

**Notes**

1. The CSV file used in this repository is for demonstration purposes.
2. This project is intended for learning and demonstration of SSIS ETL workflows.

**Author**

SSIS ETL project created for learning and demonstration of CSV-to-database data pipelines.
