# Capstone-Project

### Project Title: Sales Performance Analysis for a Retail Store

### Table of Content
[Introduction](#Introduction)

[Project Overview](#Project-Overview)

[Data Source](#Data-Source)

[Tools Used](#Tools-Used)

[Project Summary](#Project-Summary)

[Data Analysis](#Data-Analysis)

[Virtual Analysis and Inference](#Virtual-Analysis-and-Inference)


### Introduction 
---

Data analysis is crucial today as it turns raw data into insights that guide decision-making and strategy. This project evaluates retail sales performance by analyzing product, regional, and monthly trends. Using Excel for exploration, SQL for extraction, and Power BI for visualization, it will deliver an interactive dashboard summarizing key sales insights  of sales performance.

### Project Overview
---

This project seeks to analyze the sales performance of a retail store by exploring key metrics and insights within the sales data. This analysis will focus on identifying top-selling products, assessing regional performance, and examining monthly sales trends. The findings will be presented through an interactive Power BI dashboard designed to provide clear, actionable insights into the store's sales performance.
The data includes sales transactions across product categories, regions, and months, covering metrics like total revenue, sales counts, and customer data for KPI analysis. Initial Excel exploration will use pivot tables to calculate metrics like average sales per product and regional revenue, while SQL will handle complex extractions, such as top products, regional sales contributions, and monthly sales tracking.

### Data Sources
---

The primary source of data used here is data sales and this is an open source data that can be freely downloaded from an open source online such as Kaggle or any other repository site.

### Tools Used
---

- Microsoft Excel  
  1. For Data Cleaning
  2. For Analysis
  3. For Visualiation
     
- SQL - Strutured Query Language for Quering Data
  
-  Power BI
  1. For Data Cleaning
  2. For Visualization
  3. Interractive Dashboard

### Project Summary
---

The proejct  was designed to addres the following goals;

- Revenue by Product : This is the total sales revenue generated by each product over a specific period. Analyzing revenue by product helps identify which products contribute most to the store’s earnings and can guide decisions on product focus and inventory management.

- Revenue by Region: This metric shows the total revenue generated from sales in each geographical region where the store operates. It provides insights into regional demand, helps allocate resources effectively, and allows the business to tailor marketing strategies to different areas.
  
- Top selling Product: This refers to the product with the highest sales or revenue within a given timeframe.
  
- Monthly Sales : Monthly sales represent the total revenue generated in each month. Tracking monthly sales helps identify trends, seasonal fluctuations, and periods of high or low demand.

- Average Sales: is a metric that represents the mean amount of sales revenue generated over a specified period. It is calculated by dividing the total sales revenue by the number of sales transactions.

### Data Analysis
---

  - In order to begin the analysis, remove duplicate from your dataset.
 
  - Then find the total revenue and the average revenue of the sales data.
 
  - After which, a pivot table will be created in order to analyze our data.
    
   1. To calculate the total revenue by region, we need to use =Quantity X Unit Price

  ``` Excel
  =F2 X G2 
  ```

![Total Revenue](https://github.com/user-attachments/assets/082e02f7-e3df-4d44-a77b-c54724753f2d)

  2. To calculate the average revenue by region, we need to use the AVERAGEIF function because we are caculating the average revenue for several regions.

  ``` Excel
  =AVERAGEIF(C:C,C2,H:H)
  ```

![Average Sales](https://github.com/user-attachments/assets/5aa15628-f01b-4089-b114-920e83213312)

### Virtual Analysis and Inference 
---

 1. Revenue by Region                                                                                                    
    
![REVENUE BY REGION](https://github.com/user-attachments/assets/6fd0b2cd-7f1a-4e75-984d-067c4d1467a2)

2. Revenue by Product
   
![Revenue by Product](https://github.com/user-attachments/assets/4b5baa78-adda-4325-9534-0bc2357b399d)


   
