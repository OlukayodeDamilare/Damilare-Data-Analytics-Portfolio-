# Damilare-Adidas Sales Analysis

## Overview
To provide actionable insights from Adidas sales data by tracking trends, KPIs, and top products to support smarter business decision.
---

  ## Introduction
The project explores and simulates a real world sales data to analyze revenue trends, product performance and regional sales distribution using data cleaning, transformation and visualization techniques, the datasets was converted into meaningful insights through an interactive dashboard.

## Tools

+ Microsoft Power Query: Used for loading and cleaning the datasets into a suitable format for analysis.
+ Power BI: Used for addition of measures and column and data visualizations.

## Problem statement

+ Show the total revenue,operating profit and unit solds
+ Identify top selling products
+ Identify the top 5 state with highest revenue
+ Identify the region that generated the highest revenue
+ See sales trend over time.


## Power BI concepts applied:
DAX Concepts: Calculated column, measures, calender table created
Data Modelling: Star schema

## Data Sourcing: 
The data was given by the company in excel format, i downloaded the csv files and extracted it into power BI for cleaning, analysis and visualization.

## Datasets

## Features:
+ Sales ID
+ Retailer
+ Retailer ID
+ Invoice Date
+ Region
+ State
+ City
+ Product
+ Price Per Unit
+ Unit Solds
+ Total Sales
+ Operating Profit.
![DATASETS](https://github.com/user-attachments/assets/0a61d02b-1273-46f9-88c6-5ebc06e38175)

## Data preparation before visualiztion

A Date table was created to enhance visualization to see sales trend over time.
![New Date table created](https://github.com/user-attachments/assets/c96db1f9-fa49-476c-ab2f-b263d37e3d20)


A relationship (Star Schema) was created to enhance the vusializations and have accurate result
## Objective
+ To combine data from multiple tables to help power BI understand how the table are connected
+ To enable accurate visuals
+ To avoid data duplication
+ To support advanced calcutions (DAX).
![A relationship was created to enhance the visualization](https://github.com/user-attachments/assets/ec71a42e-af2b-4919-ac40-655c0432698d)

## DATA ANALYSIS
  # Top selling Products
  + Men's street footwear generated the highest revenue with 27.7M in Sales,
    while Women's athletic footwear had the lowest revenue with 14.3M in sales due to everyday and occasion based use, men's street footwear(sneakers, casual shoes is worn daily for work or casual events while women's athletic footwear is purchased for specific activities like workouts or sport thereby reducing purchase frequency.
    
    ![Top selling products](https://github.com/user-attachments/assets/8b4269d9-ec82-4acd-a9e0-4e28b7671a2e)

    # Top 5 states with highest revenue
    + Washington generated the highest sales with 3.2M in Sales which is highesr than other locations due to strong urban & tech-driven economy,
       washington (especially seattle) has high concentration of tech companies and high income earners which leads to higher disposable income and willingness to spend more on premium and branded products.

      
![Top 5 states](https://github.com/user-attachments/assets/92f6976c-0210-4fa3-9a98-8ac6ae50eb2e)

   # Which region generated the highest revenue
   West region (36.3M in Sales) generated the highest revenue followed by Northeast(25.1M in Sales) while Midwest generated the lowest revenue with 16.7M in Sales.

   ![Which region generated the highest revenue](https://github.com/user-attachments/assets/af941d18-c8fa-4229-84ff-7da6a3617626)

# Monthly Sales Trend
July was our peak month in sales generating 12.5M in Revenue, this is because there is higher consumer spending due to mid-year bonuses, holidays and events and there's strong retail and online marketing during this period 
- Seasonality + Promotions = Sales Spike.
WHILE while march and february (respectively) had the lowest sales simply because consumers prioritize essentials expenses early in the year
- Reduced consumer activities = Lower Sales Volume.
  
![Monthly sales trend](https://github.com/user-attachments/assets/2b5cc97e-d614-43cb-98f0-260acef88f57)

# Total sales and Total operating profit by each retailer
West gear Retail shop generated the highest sales and operating profit followed by foot locker retail shop, this is because they have better pricing control and fewer discounts while amazon had the lowest sales and operating profit because sales is spread across many third-party sellers thereby leading to higher operational and fulfilment cost so this greatly affect their operating profit.

![Total operating profit and Total sales per each retailer](https://github.com/user-attachments/assets/c9842b9d-078d-4c50-8978-9972bff3423b)

## DATA VISUALIZATION
![Adidas Dashboard image](https://github.com/user-attachments/assets/62eeaefc-03fe-413b-8a6c-5bda5552cba9)


## INSIGHTS

+ Overall Performance: Total sales amounted to $120M with a total operating profit of $33M from 2M units sold, indicating a healthy average price per unit of $45.
+ Regional Dominance: The West region generated the highest sales by a significant margin ($36M), followed by the Northeast ($25M).
+ West Gear (Top Retailer): is the leading retailer, contributing the most to both total sales ($32M) and units sold (0.60M).
+ Men's Street Footwear : is the top-selling product (27.7M), closely followed by Women's Apparel (23.8M).
+ Washington is the Geographic Hotspot: had the highest sales ($3.22M), with Virginia coming in second ($3.07M).

## RECOMMENDATIONS

+ Capitalize on Regional Success: Invest further in marketing and inventory in the West and Northeast regions to maintain sales momentum.
+ Optimize Product Mix: Ensure consistent stock availability for Men's Street Footwear and Women's Apparel, as they are the primary revenue drivers.
+ Strengthen Retailer Partnerships: Collaborate with West Gear to explore opportunities for increased market penetration and potentially incentivize other retailers like Amazon and Walmart to boost their sales.
+ Targeted State Campaigns: Focus marketing efforts on top-performing states such as Washington and Virginia to maximize local market potential.


