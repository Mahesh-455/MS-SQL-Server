# SSAS Cube Project
This repository contains a **SQL Server Analysis Services (SSAS)** cube project developed using Microsoft Visual Studio.
The project demonstrates the creation of a multidimensional cube, including data sources, data source views, dimensions, and measure groups.

**Technologies Used**
1. Microsoft Visual Studio 2026 Community Edition
2. SQL Server 2022 Developer Edition
3. SQL Server Analysis Services (SSAS)
4. SQL Server Management Studio (SSMS)
5. Microsoft Excel (for cube analysis)

**Project Structure**
The SSAS solution was created in Visual Studio. The following project files and folders are generated as part of the solution:

1. .sln → Solution file
2. .dwproj → SSAS project file
3. /Data Sources/ → Data source definitions
4. /Data Source Views/ → Data Source View (DSV) files
5. /Cubes/ → Cube definition XML files
6. /Dimensions/ → Dimension definition files
7. /Roles/ → Security role definitions
8. /Deploy/ or /bin/ → Deployment artifacts generated during build and deployment

**Files Overview**
Below is the overall files created in the repository folder.

<img width="911" height="521" alt="image" src="https://github.com/user-attachments/assets/ad0370a7-bad3-4233-b755-dfbe7788b922" />

**SSAS Solution Overview**
Below is the overall solution structure created in Visual Studio.

<img width="674" height="535" alt="image" src="https://github.com/user-attachments/assets/a992fd27-b7b1-468e-b59e-5bc510072964" />

**Sample view of the SSAS cube report**

<img width="1377" height="620" alt="image" src="https://github.com/user-attachments/assets/6fab7bf7-c5bd-4639-a516-dbb0371189d8" />

**SSAS Cube Template Used**
The cube was created using the Analysis Services Multidimensional and Data Mining Project template in Visual Studio.

<img width="712" height="149" alt="image" src="https://github.com/user-attachments/assets/921f33bb-f67d-4cf7-a4af-e027826274b1" />


**SSAS Database Deployment**
Once the cube is deployed from Visual Studio, a new SSAS database is created on the Analysis Services instance.
This database can be viewed by connecting to the SSAS instance using SQL Server Management Studio (SSMS).

<img width="461" height="655" alt="image" src="https://github.com/user-attachments/assets/4e98e1cc-f213-426d-bf1a-4c50c8ed15c0" />

<img width="520" height="693" alt="image" src="https://github.com/user-attachments/assets/26734941-7a0a-4074-ac0a-4e44edc5cf4b" />

**Querying the Cube**

The cube can be queried and analyzed using multiple tools, including:
1. SQL Server Management Studio (SSMS)
2. Microsoft Excel
3. Visual Studio cube browser
4. Example cube query results:

<img width="1801" height="822" alt="image" src="https://github.com/user-attachments/assets/fef06b69-8ff1-47f8-9696-e8b350100371" />

**Cube Analysis in Excel**
SSAS cubes can also be explored using Microsoft Excel PivotTables, allowing users to analyze multidimensional data interactively.

<img width="649" height="332" alt="image" src="https://github.com/user-attachments/assets/8062fd5d-0da8-4355-ba08-11ac2b030d18" />

**Notes**

1. The cube must be built and deployed to an SSAS instance before it can be queried.
2. Deployment creates a database inside the Analysis Services server.

**Author**

SSAS Cube Project created for learning and demonstration purposes using SQL Server Analysis Services.
