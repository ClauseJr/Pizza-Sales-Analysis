# Pizza Sales Analysis (2015)



### Project Overview

This data analysis project aims to provide insights into the sales performance of a Pizza Outlet in 2015. By analyzing various aspects of sales data, we seek to identify trends in price performance, revenue behavior, sales management, make data driven recommendations and gain a deeper understanding of the company's performance. This project demonstrates full-stack data skills from data cleaning to interactive dashboard creation.


### Data Sources
Pizza Sales Data: The primary dataset of this analysis is from [kaggle.com](https://www.kaggle.com/) containg the following tables:
  - [order_details.csv](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales?select=order_details.csv)
  - [orders.csv](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales?select=orders.csv)
  - [pizza_types.csv](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales?select=pizza_types.csv)
  - [pizzas.csv](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales?select=pizzas.csv)


### Tools Used
a. Excel:
  - Power Query for data cleaning and transformation
  - Pivot Tables for initial analysis
  - XLOOKUP for data validation

b. Power BI:
  - Power Query Editor for data modeling
  - DAX for calculated measures and columns
  - Custom visuals
  - Bookmarks for interactive storytellings


### Step-by-Step Processes

Phase 1: Data Cleaning and Preparation

In the initial data preparation process, we performed the folloing tasks:
  1. Data loading and Inspection.
  2. Handling missing values and nulls.
  3. Handling Duplicates and Identifying inconsistencies in Dates.
  4. Data cleaning and formating.

Phase 2: Data Modeling & Analysis (Power BI)

In Data modeling, we performed the following tasks:
  1. Implemented a snowflex schema with order_details as fact table
  2. Established relationships using pizza_id, pizza_type_id and order_id
  3. Created a custom Dates table using DAX for period analysis
