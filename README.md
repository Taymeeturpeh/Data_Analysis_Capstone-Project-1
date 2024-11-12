# Data_Analysis_Capstone-Project-1

### Capstone Project-1 Title: Sales Performance Analysis for a Retail Store using Excel, Sql and Power bi

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

 [Data Analysis and Insight](#data-analysis-and-insight)

 [Data Visualization](#data-visualization)

 [SQL](#sql)

  [Visualizations](#visualizations)

  [Power Bi](#power-bi)

  [Visualization](#visualization)




### Project Overview
This Project provides an analysis of a sales performance for a retail store using the given data set by Incubator Hub. This project involves data cleaning, exploratory data analysis and visualization in EXCEL, querying in SQL and interactive reports in POWER BI.

### Data Sources
The source of the data used for this capstone project was provided by the The Incubator Hub.

### Tools Used
- Microsoft Excel for Data cleaning, Data Analysis and Visualization.
- SQL(Structured Query Language) for Querying data.
- Microsoft Power Bi for interactive reports.
- Github for Portfolio building.

### Data Analysis and Insight
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


 ### SQL

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
### Visualizations

![Q1](https://github.com/user-attachments/assets/e268228b-06de-447d-86b1-ea43c01deea9)
![Q2](https://github.com/user-attachments/assets/b2bf985d-3bb1-4223-8589-d6268238f5b6)
![Q3](https://github.com/user-attachments/assets/8b708420-1247-4866-a2c3-ef16a803ca66)
![Q4](https://github.com/user-attachments/assets/6562d7b8-e49b-4815-b8ef-8fa3b6726e0e)
![Q5](https://github.com/user-attachments/assets/28cad898-7b24-4bb1-a033-86201532f22c)
![Q6](https://github.com/user-attachments/assets/3cd0eae4-9a22-4bee-a4bb-0e903688fba5)
![Q7](https://github.com/user-attachments/assets/b11542f2-1508-4ca5-b330-9da67b52a68a)
![Q8](https://github.com/user-attachments/assets/5aa9ca96-3cbe-4082-b0fb-23d5f02c9c40)


### Power Bi
I designed a power bi dashboard that allows the exploratin of key metrics like total sales, product performance and sales trends over time. The dashboard includes several interactive visuals and filters for a user-friendly experience.

### Visualization

![Powerbi dashboard(sales perf)](https://github.com/user-attachments/assets/d2bc3218-d8cb-488f-9518-9ff45b9c6bce)
