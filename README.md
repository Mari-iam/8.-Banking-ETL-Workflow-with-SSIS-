# Banking ETL Workflow with SSIS
## Project Overview
This project involves transferring banking data from an OLTP (Online Transaction Processing) system to a DWH (Data Warehouse) in SQL Server using SQL Server Integration Services (SSIS). Once the data is available in the DWH, Power BI is used to create reports, find insights, and visualize the data for enhanced decision-making.

## Features
* Data Transfer: Seamlessly extract, transform, and load (ETL) banking data from the OLTP system to the DWH using SSIS.
* Data Integration: Handle foreign key relationships and other constraints during data integration into the DWH.
* Reporting & Visualization: Use Power BI to generate insightful reports and visualize trends in the banking data.
* Key Metrics: Analyze account balances, loan statuses, customer details, branch performance, and more using advanced visualizations.

##bComponents
### 1.SSIS (SQL Server Integration Services)

* Source System (OLTP): Banking data from an OLTP database.
* Target System (DWH): Data Warehouse schema to store historical data, which facilitates analytical reporting.
* ETL Process: SSIS package designed to extract data from OLTP, transform it as necessary (e.g., data cleansing, type conversion), and load it into the DWH.
### 2.Power BI

* Data Connection: Power BI connects to the DWH to retrieve data.
* Reports & Dashboards: Custom visualizations, charts, and graphs built to provide insights into various aspects of the banking data such as:
* Account details
    * Loan statuses
    * Branch performance
    * Transaction trends
## Steps to Run the Project
### 1.SSIS (ETL Process)
1.Set up OLTP and DWH Databases:
* Create the OLTP and DWH schema in SQL Server.
* Populate the OLTP database with sample banking data.

2.Configure SSIS Packages:
* Use SSIS to create ETL packages for extracting data from the OLTP system and loading it into the DWH.
* Ensure foreign key constraints and relationships are handled correctly during data migration.

3.Execute SSIS Package:
* Run the SSIS package to transfer data from the OLTP system to the DWH.

### 2.Power BI (Reporting & Visualization)
1.Connect to the DWH:
* Open Power BI and establish a connection to the SQL Server DWH.

2.Create Reports and Dashboards:
* Use Power BI to create interactive reports and dashboards based on the DWH data.
* Explore various dimensions (Account, Loan, Customer, Branch) and generate insights.

## Insights and Analytics
Using Power BI, key insights such as customer behavior, loan repayment trends, branch performance, and account balances can be visualized and analyzed to make data-driven decisions.

## Tools & Technologies
* SQL Server: For OLTP and DWH database management.
* SSIS (SQL Server Integration Services): For ETL processes to move data from OLTP to DWH.
* Power BI: For reporting and visualization of DWH data.
* T-SQL (Transact-SQL): Used for querying data within SQL Server.
