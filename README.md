# Data_Analysis_Capstone-Project-1

### Capstone Project-1 Title: Sales Performance Analysis for a Retail Store using Excel, Sql and Power bi

### Project Overview
This Project provides an analysis of a sales performance for a retail store using the given data set by Incubator Hub. This project involves data cleaning, exploratory data analysis and visualization in EXCEL, querying in SQL and interactive reports in POWER BI.

### Data Sources
The source of the data used for this capstone project was provided by the The Incubator Hub.

### Tools Used
- Microsoft Excel for Data cleaning, Data Analysis and Visualization.
- SQL(Structured Query Language) for Querying data.
- Microsoft Power Bi for interactive reports.
- Github for Portfolio building.

### Data Analysis and Insight(Excel)
- Data Exploration 
  1. Data Cleaning: I identified and handled missing values and removed duplicates to ensure data accuracy.
  2. Summary Statistics: I used functions like SUM, AVERAGE and COUNT to understand overall sales ad average revenue per transaction
  3. Pivot Tables: Pivot table summarizes sales by categories, region or periods to spot trends and compare performance.
  4. Data Visualization: I created charts(bar chart and pie chart) to visualize product performance and seasonal pattern.
  
- Data Analysis: This is where some basic line of code in my analysis are included.
  1. SUM FUNCTION: Adds up a range of numbers
     ``` Excel
     SUM(B2:B100)
     ```
  2. AVERAGE FUNCTION: Calculate the average(mean) of a range of numbers.
     ```Excel
     AVERAGE(C2:C100)
     ```
  ### Data Visualization

  ![SalesData image](https://github.com/user-attachments/assets/e7b8d519-eb0d-4d9b-880f-bc63c07c9a68)

![pivot table summary](https://github.com/user-attachments/assets/ca8ec8a6-1134-440f-a293-d89b3e388cf4)

![Dashboard of sales performance](https://github.com/user-attachments/assets/6e47f307-3ab9-4a83-a491-1bd6e0aa9fca)


 ### SQL(Structured Query Language)

 Below are some lines of code used in my query.
 
 ```SQL
SELECT PRODUCT, SUM(TOTAL_SALES)AS TOTALSALES
FROM SalesData
GROUP BY PRODUCT
```

```SQL
SELECT TOP 1 PRODUCT, SUM(TOTAL_SALES) AS HIGHESTSELLINGPRODUCT
FROM SalesData
GROUP BY PRODUCT
```


