**SSRS Report Project**
This repository contains a SQL Server Reporting Services (SSRS) project developed using Microsoft Visual Studio.
The project demonstrates how to create, design, and deploy reports that visualize data from SQL Server databases.

**Technologies Used**

1. Microsoft Visual Studio 2026 Community Edition
2. SQL Server 2022 Developer Edition
3. SQL Server Reporting Services (SSRS)
4. SQL Server Management Studio (SSMS)

**Project Overview**

The SSRS project includes:
1. Data Sources – Connections to SQL Server databases
2. Datasets – Queries used to retrieve report data
3. Reports – Paginated reports designed in Visual Studio
4. Report Parameters – Allow filtering and dynamic report behavior
5. Deployable Project – Ready to publish to an SSRS server

**Project Structure**

When the SSRS solution is created in Visual Studio, the following files and folders are generated:
1. .sln → Solution file
2. .rptproj → SSRS project file
3. /Reports/ → Report definition files (.rdl)
4. /Shared Data Sources/ → Shared database connections
5. /Shared Datasets/ → Optional shared datasets
6. /bin/ or /obj/ → Build output files

<img width="661" height="321" alt="image" src="https://github.com/user-attachments/assets/fc9bb4e6-8451-4122-8a55-bcf826157e68" />

**Solution Explorer View**

The SSRS project in Visual Studio appears as follows:

<img width="1918" height="482" alt="image" src="https://github.com/user-attachments/assets/8f0fcbdc-d082-4049-b7ae-da2af3935b60" />

**Example Report View**

The project includes a sample report visualizing data from a SQL Server table

<img width="820" height="895" alt="image" src="https://github.com/user-attachments/assets/73c68e1a-3350-4f87-a06e-17dd0125d53c" />

**Querying the Data**

Reports are backed by SQL queries  in SQL Server. Example query used in one of the reports:

SELECT   Name AS [Product Name], ListPrice AS [List Price], SellStartDate AS [Sell Start Date], SellEndDate AS [Sell End Date]
FROM     Production.Product
ORDER BY [Product Name], [List Price]

**Deployment**

1. Open the solution in Visual Studio
2. Configure data source connections to point to your SQL Server instance
3. Build the project
4. Deploy the reports to the SSRS server
5. Reports can then be accessed via SSRS Web Portal, Report Manager, or direct URL access.

**Use Cases**

This project demonstrates:
1. Creating interactive reports with parameters
2. Using SSRS to visualize SQL Server data
3. Preparing reports for business intelligence and decision-making
4. Paginated reporting for print-ready outputs

**Notes**

The sample data used in the reports is for demonstration purposes.

**Author**

SSRS Report Project created for learning and demonstration of reporting solutions using SQL Server Reporting Services.
