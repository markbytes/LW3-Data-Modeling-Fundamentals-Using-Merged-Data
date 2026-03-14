# LW3-Data-Modeling-Fundamentals-Using-Merged-Data

# Part 1: Review the Merged Dataset
![Description](https://github.com/markbytes/LW3-Data-Modeling-Fundamentals-Using-Merged-Data/blob/7f93c93901253f2045841264a724642eb9fa7da1/1.png)
# Guide Questions
1. Is the dataset in flat-table format?
   - Yes
2. Which columns describe customers?
   - The columns that describe customer details are CustomerID, CustomerName, City, and Region
3. Which columns represent transactions?
   - OrderID, OrderDate, and SalesAmount

# Part 2: Identify Fact and Dimension Tables
Create DimCustomer table
![Description](https://github.com/markbytes/LW3-Data-Modeling-Fundamentals-Using-Merged-Data/blob/4d7fd1ee299e54e001aa6f32fdc43d6b39238607/2.png)<br><br>

Create FactSales table
![Description](https://github.com/markbytes/LW3-Data-Modeling-Fundamentals-Using-Merged-Data/blob/4d7fd1ee299e54e001aa6f32fdc43d6b39238607/3.png)

Guide Questions
1. Why must dimension tables contain unique keys?
   - Dimension tables need unique keys so Power BI has a single, definitive "source of truth" to look up when it's trying to figure out exactly which customer or product belongs to a specific sale.
2. What problems occur if duplicates exist in DimCustomer?
   - If you have duplicates, Power BI gets confused and often "double-counts" your numbers, making your total sales look much higher than they actually are because it's attaching the same transaction to the same customer multiple times.

# Part 3: Define Primary & Foreign Keys

