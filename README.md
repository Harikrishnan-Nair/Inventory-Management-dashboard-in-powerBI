# Inventory-Management-dashboard-in-powerBI

Inventory management dashboard was created in powerBI based on the data of stock and past orders. This data is of years 2019 and 2020, however for the consistency in analysis round the year I have filtered the data models for year 2019 and following that the models were build 
This dataset has columns as below:
In Stock sheet-
1. SKU ID
2. Current Stock Quantity
3. Units (Nos/Kg)
4. Average Lead Time (days)
5. Maximum Lead Time (days)
6. Unit Price

In Past Orders sheet-
1. Order Date
2. SKU ID
3. Order Quantity

The data was first loaded to powerBI and following that other columns were added based on the respective calcualtions and categorisation for the visualization purpose:
![Inventory Dashboard Sample page1](https://github.com/Harikrishnan-Nair/Inventory-Management-dashboard-in-powerBI/assets/95662379/fbdfef76-93f6-4839-a920-1b53b7c88916)

Key Insights:
1. 95% of products require to be reordered in order to streamline the inventorial processes
2. Inventory Turnover Rate(ITR), the metric of how efficiently inventory is functioning has some scope for improvement and this can be achieved carefully stocking the SKUs of Y[Variable demand] and Z[uncertain demand]
              Inventory Turnover Rate = Cost of Goods sold annually / Avg Inventory Value in warehouse
3. SKUs of A Class and X-Category brings in the highest revenue whereas SKUs of B Class and Y-Category are present in the warehouse(excluded A Class since that is contributing for more revenue).



