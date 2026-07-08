# Supply Chain Visibility & Optimization - Milestone 1

## Objective
Build a clean and efficient star schema data model in Power BI for supply chain analysis. This milestone focuses on data import, preprocessing, data modeling, and relationship creation.

## Dataset Source

The dataset used in this project was provided by Infosys as part of the Supply Chain Visibility & Optimization Internship.

Original public dataset:
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Data Cleaning and Transformation Steps
- Imported the dataset into Power BI.
- Checked and handled missing values.
- Removed duplicate records.
- Corrected data types.
- Renamed tables and columns where required.
- Created Fact and Dimension tables using Power Query.
- Added index columns for surrogate keys.
- Merged queries to create Location and Shipping dimension keys.
- Created a Date dimension table using DAX.
- Added Year, Month, Quarter, Week, Day, and Day Name columns.

## Data Model Overview
A Star Schema was created with:
- Fact_table
- Dim_Customer
- Dim_Product
- Dim_Category
- Dim_Department
- Dim_Location
- Dim_Shipping
- Dim_Date

Relationships were created using one-to-many cardinality, with Order Date as the active relationship and Shipping Date as the inactive relationship.

## Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- GitHub
