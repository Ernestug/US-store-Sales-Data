# US-store-Sales-Data
## This project highlights the sales performance of a US-based store across different states, showing the number of sales generated from 2014 to 2017 with respect to product categories, customers, location, etc.

##  Data Cleaning

The dataset used for this analysis was gathered from [Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting). The data was sourced as a CSV file and was cleaned in Excel - ensuring there are no duplicates, no blank rows, using appropriate data types, and deleting unwanted columns. After cleaning and transformation was completed, the data was converted to a table called Sales Data, and different pivot tables were created.

## Creating Pivot Tables

Pivot tables were created from the Sales Data table. Pivot tables for Customers, Orders, Products, and Location was created. In these Pivot tables, VLOOKUP function was used to return the value of respective data as new columns from the main Sales Data Table. These pivot tables were then converted to normal tables by copying and pasting as values. This is to allow relationships to be created effectively.

## Creating Relationships

Data modelling was also done after the pivot tables were created. Using Customer ID, Product ID, Order ID, and Postal code as the primary keys in the Customers, Products, Orders, and Location tables respectively; 4 new relationships were created by linking the primary keys from these tables with the foreign keys from the Sales Data table.

## Pivot Charts & Dashboard

After the relationships have been created, a sheet was created where various pivot charts and tables were housed. These pivot charts were created to build a simple dashboard which highlights the sales performance across different metrics at a glance. The charts were created with respect to sales performance based on customers, product category, states, segment, etc. In addition to charts, slicers and timeline were also created to make the dashboard interactive and easy to navigate through. The CSV file downloaded from the source was attached. Also, the final file containing the dashboard, tables, and various other transformations was also attached.


## Remarks

Some insights I was able to generate from this analysis are outlined below:

- **Profit Trend:** There was a steady growth in profit from 2014 to 2017. However, the business recorded lossses in some specific months. The months of July 2014 and January 2015 brought in losses for the company.
- **Customer with the highest number of sales:** "Sean Miller" was the customer who generated the highest sales for the company. Majority of his sales came in 2014 where he bought products worth over $23,0000.
- **Top Performing States based on sales:** California and New York generated the highest sales from 2014 to 2017, amounting to over 33% of total sales for the company.

![](https://github.com/Ernestug/US-store-Sales-Data/blob/main/US%20Sales%20Data%20Dashboard.png)
