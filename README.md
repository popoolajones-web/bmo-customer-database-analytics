BMO Customer Database Analytics

Independent SQL Server Database Design & Customer Analytics Project

Project Overview

This project focuses on designing and exploring a relational database for customer information management, using a BMO-themed business scenario.

The database contains 1,000 synthetic customer records and related reference and operational tables. It was designed in Microsoft SQL Server to demonstrate relational database modelling, data organisation, table relationships and SQL-based business analysis.

The project provides an opportunity to explore how structured customer data can support operational reporting, customer relationship management and business intelligence.

Data Disclaimer: This is an independent educational portfolio project. It uses synthetic data and is not affiliated with, commissioned by, or representative of Bank of Montreal (BMO). No actual customer information or proprietary BMO data is used.

Project Objectives

* Design a relational database for customer information management.
* Establish relationships between customer, address and reference tables.
* Organise customer and staff information using relational database principles.
* Practise SQL querying and data retrieval.
* Develop business-focused analytical questions.
* Demonstrate how structured data can support reporting and decision-making.

Tools & Technologies

Tool	Purpose
Microsoft SQL Server	Relational database management
SQL Server Management Studio (SSMS)	Database development and management
SQL	Data querying and analysis
SQL Server Database Diagrams	Visualising table relationships
GitHub	Project documentation and version control

Database Structure

The database includes the following tables:

Table	Purpose
tblCustomer	Stores customer information
tblCustomerAddress	Stores customer address records
tblAddressType	Defines address categories
tblCity	Stores city reference information
tblState	Stores state or province reference information
tblStaff	Stores staff information
tblDesignation	Defines staff designations
tblGender	Stores gender reference values
tblStaffRewards	Stores staff reward records
tblRewardTypes	Defines reward categories
tblPromotionGift	Stores promotional gift information

Database Design & Relational Modelling

The database was created using a relational database design approach.

Tables are connected through primary and foreign key relationships to organise information and establish logical links between customer, address, staff and reference data.

A SQL Server database diagram is included in the project documentation to illustrate the relationships between the tables.

Dataset

* Records: 1,000 synthetic customer records.
* Data type: Artificially generated customer information.
* Structure: Multiple related relational tables.
* Purpose: Database design, SQL practice and business analytics.

Planned SQL Analysis

The project will progressively incorporate SQL queries addressing business questions such as:

1. How many customers are registered in the database?
2. How are customers distributed across cities and provinces?
3. What customer information can be retrieved by joining related tables?
4. How many customers have different address types?
5. How are staff members distributed across designations?
6. What staff reward categories are represented?
7. What insights can be extracted by combining customer and reference data?

Queries and findings will be added as the analysis is completed.

Business Intelligence Applications

The database provides a foundation for demonstrating how relational data can support:

* Customer information reporting.
* Geographic customer distribution analysis.
* Customer relationship management.
* Staff and reward reporting.
* Data quality and consistency checks.
* Business intelligence and management reporting.

Project Repository Structure

The repository will progressively be organised as follows:

bmo-customer-database-analytics/
│
├── 01-Database-Design/
│   └── BMO-Database-Diagram.png
│
├── 02-Table-Documentation/
│
├── 03-Sample-Data/
│
├── 04-SQL-Queries/
│
├── 05-Data-Analysis/
│
├── 06-Visualizations/
│
└── README.md

Project Status

In Progress

Database design and synthetic customer data preparation have been completed. Documentation, SQL analytical queries, business findings and visualisations will be added as the project develops.

Author

Popoola Jones

Aspiring Business Intelligence and Data Analytics Professional

Interested in SQL Server, relational database design, data analytics, business intelligence and data-driven decision-making.
