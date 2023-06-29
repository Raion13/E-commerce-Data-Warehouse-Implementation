# E-commerce-Data-Warehouse-Implementation
Part of Virtual Internship from Rakamin X ID/X Partners.

1. Background:

As a Data Engineer at ID/X Partners, I have been assigned a project for a client in the e-commerce industry. The client's requirement is to build a Data Warehouse that consolidates data from various tables in their source database. The Data Warehouse will consist of a Fact table and several Dimension tables. The objective is to provide the client with a centralized and optimized data repository for analysis and reporting purposes.

2. Problem Definition:

The client needs a robust Data Warehouse solution to effectively analyze their e-commerce data. They want to streamline reporting, gain insights, and make data-driven decisions. The project involves importing the data into a staging environment, creating the Data Warehouse schema, implementing ETL processes, and developing a stored procedure for generating summary sales order reports based on delivery status.

3. Objective:

The objective of this project is to successfully implement a Data Warehouse solution for the e-commerce client, enabling efficient data analysis and reporting. The Data Warehouse should accurately reflect the business processes and support the client's decision-making needs.

4. Tools:
- SQL Server & SQL Server Management Studio
- Talend

5. Steps:

a. Import/Restore Database Staging
- Import or restore the database into the staging environment.
- Importing the database into the staging environment is a crucial initial step for further data processing and transformation.

b. Create DWH_Project Database and Tables
- Create a new database named "DWH_Project". Design and create the Fact table and Dimension tables based on the relevant tables in the staging database.
- Creating a dedicated database and designing the appropriate schema is essential for organizing the Data Warehouse effectively.

c. Develop ETL Job with Talend
- Create a job in Talend to extract data from the staging tables and load it into the corresponding Fact and Dimension tables in the DWH_Project database. Implement data transformation logic for the DimCustomer table to capitalize the FirstName and LastName columns and combine them into a new column called CustomerName.
- Talend provides powerful ETL capabilities, enabling efficient data extraction, transformation, and loading. Transforming the customer name data aligns with the client's requirements and enhances data consistency.

d. Create Summary Sales Order Stored Procedure
- Define a stored procedure in SQL Server that generates a summary report of sales orders based on their delivery status. Implement the necessary SQL queries to aggregate and summarize the sales order data. Ensure the stored procedure accepts relevant parameters and returns the desired result set.
- Creating a stored procedure simplifies the process of generating summary reports and allows for parameterized queries, increasing flexibility and efficiency in retrieving the required information.
