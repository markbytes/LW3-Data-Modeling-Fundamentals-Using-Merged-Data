# LW3-Data-Modeling-Fundamentals-Using-Merged-Data
# PDF LINK
https://docs.google.com/presentation/d/1DGsunJ6C6BfRWZI7gGyqW9hxTP8TmYxOKuakjKzYb-Q/edit?usp=sharing
# Guide Questions
1. Is the dataset in flat-table format?
   - Yes
2. Which columns describe customers?
   - The columns that describe customer details are CustomerID, CustomerName, City, and Region
3. Which columns represent transactions?
   - OrderID, OrderDate, and SalesAmount

# Guide Questions
1. Why must dimension tables contain unique keys?
   - Dimension tables need unique keys so Power BI has a single, definitive "source of truth" to look up when it's trying to figure out exactly which customer or product belongs to a specific sale.
2. What problems occur if duplicates exist in DimCustomer?
   - If you have duplicates, Power BI gets confused and often "double-counts" your numbers, making your total sales look much higher than they actually are because it's attaching the same transaction to the same customer multiple times.



