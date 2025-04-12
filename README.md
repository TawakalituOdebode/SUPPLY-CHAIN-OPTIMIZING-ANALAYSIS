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


## KEY INSIGHTS AND RECOMMENDATIONS:

**INSIGHTS**

**SALES AND REVENUE**

-Total revenue of $578k indicates high sales performance, with a total cost of $58k, comparatively lower to the revenue generated, suggesting good profitability.

-The skincare product type has the highest contribution of 40%, with $241.63k, followed by haircare's 30% and cosmetics' 28%.

-The unknown customer demographic segments lead in revenue generation.

-Products with SKU 8,2,31,32, and 38 are top 5 revenue contributors.

-Stock level of 4,777 suggest sufficient stock availability.

**SUPPLIER AND LOGISTICS PERFORMANCE**

-Supplier 4 and Supplier 1 are the most reliable with the lowest lead times. Also, Supplier 3 has the highest lead times, highlighting potential inefficiencies.

-Carrier B has the highest defect rates, suggesting potential issues with handling or logistics.

-Sea transport is the most cost-effective judging from the low shipping cost incurred.

-Most suppliers have passed inspections, with a few pending or failing, emphasizing a need for quality control for certain suppliers.

-Haircare have the highest defect rate, followed by skincare, which suggests potential quality or manufacturing issues in these categories.


**INVENTORY AND STOCK MANAGEMENT**

-Skincare has the highrst order quantities but a relatively lower stock level was recorded, indicating understock.

-Supplier 2 has the highest production volume but lower product sold, suggesting potential overproduction or sales inefficiencies. However, Supplier 5 shows better alignment between production and sales.

### RECOMMENDATIONS

-Supplier Management: Focus on improving lead times for Supplier 3. Address quality control issues with Carrier B and prioritize inspections for suppliers with pending/failing results.
  
-Inventory Optimization: increase stock levels for understocked products like skincare.

-Shipping Optimization: Review the use of Carrier B and prioritize cost-effective transportation modes like sea transport.
 
-Defect Rate Reduction: Investigate high defect rates in haircare and skincare and implement quality assurance measures.

-Revenue and Sales Improvement: Products with more sales should always be in stock to boost revenue. Locations with lower sales and revenue may require localized marketing or distribution strategies.









