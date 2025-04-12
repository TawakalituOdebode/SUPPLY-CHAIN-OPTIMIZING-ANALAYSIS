# SUPPLY-CHAIN-OPTIMIZING-ANALAYSIS
This project reveals insights into a supply chain network from production to distribution, providing insights that will enable process optimization and informed business decisions.
## DATA SET:
**Data source**-Kaggle( Onyx Data challenge)

**Data Description**
 **Supply chain Analytics Data**
The dataset was collected from a Fashion and Beauty startup. The dataset is based on the supply chain of Makeup products. Below are all the features in the dataset:
Product Type, SKU, Price, Availability, Number of products sold, Revenue generated, Customer demographics, Stock levels, Lead times, Order quantities, Shipping times, Shipping carriers, Shipping costs, Supplier name, Location, Lead time, Production volumes, Manufacturing lead time, Manufacturing costs, Inspection results, Defect rates, Transportation modes, Routes, Costs

## TOOLS

-Power Query in Power BI was used for data cleaning

-Power BI was used for visualization
## DATA ANALYSIS

-**Import the Dataset**

•	Loaded the  Excel file directly into Power BI.

•	Used Power Query to clean and transform the data before loading it into the model.

-**Data Cleaning & Transformation (Power Query)**

•	Remove duplicates & errors in SKU, Supplier Name, and Product Type.

•	Convert data types (e.g., price as currency, stock levels as whole numbers).

•	Create calculated columns : 

Profit = Revenue – Costs

Stockout Risk = If Stock Levels < (Number of products sold * 0.2), then "High Stockout Risk", else "Safe".

-**Data Modelling**

•	Fact Table (contains transactions like sales, revenue, costs)

•	 Dimension Tables (contains descriptive info like product details, suppliers, and locations)

# Data Model Schema


