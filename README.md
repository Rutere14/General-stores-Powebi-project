
#  General Store Sales Power BI Project

# About

This Power BI project delves into the comprehensive analysis of sales data from a general store. The primary objectives are to uncover insights into the store's performance, product trends, and customer behaviour. By thoroughly examining the sales dataset, the project aims to identify areas for sales strategy improvement and optimization.






# About The Data

The dataset utilized in this Power BI project is sourced from Kaggle. 

## Dataset Overview

The dataset comprises 21 columns and 9,995 rows, offering a substantial volume of data for exploration and interpretation. Here is an overview of key columns in the dataset:
| Column | Description | 
|----------|----------|
| Row ID | unique identifier for the rows | 
| Order ID | unique identifier for each Order | 
|Order Date|The Date the order was placed |
|Ship Date | Date the shipping was done | 
|Ship Mode| Mode of shipping | 
|Customer ID | unique identifier for each Customer | 
| Customer Name| Names of the customer | 
| Segment| consumer, corporate or home office |
| Country| Name of the Country | 
|City | Name of the City | 
|State | Name of the state | 
|Postal Code | Postal code identifier | 
| Region| Central, East, South and West |
|Product ID| Product identifier|
|Category | Furniture, Office supplies and Technology|
|Sub-Category | Category break down e.g. table & chairs|
|Product Name | specific name of the product | 
| Sales | Sales made |
| Quantity | Units sold |
|Discount | Discount given |
|Profit| The profit made|













# Approach used.
**1. Data Wrangling:** This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.

**2. Feature Engineering:** This will help use generate some new columns from existing ones.

**3. Exploratory Data Analysis (EDA):** Exploratory data analysis is done to answer the listed questions and aims of this project.
## Time Period of the Project.

The data used in this project spans the time period of four years from 01/01/2014 to 31/12/2017. This timeframe captures the historical sales data and provides insights into the business's performance and trends during this specific period.

## Target audience for the data viz/dashboard & Purpose
**The primary audience for this data visualization/dashboard includes:**
- **Business Stakeholders:** Executives, managers, and decision-makers seeking a comprehensive understanding of sales performance and customer behaviour.
- **Marketing Teams:** Analyzing product trends, promotional effectiveness, and customer segmentation.
- **Sales Teams:** Identifying top-performing City, state, Region, Categories, and opportunities for improvement.
  
**The dashboard is designed to help users achieve the following objectives:**
- Gain insights into overall sales trends and patterns.
- Identify top-performing states/City and products.
- Understand customer behaviour and preferences.
- Optimize sales strategies and marketing campaigns.

# Tools Used 
* Power BI.
- link to the interactive dashboard
 https://app.powerbi.com/view?r=eyJrIjoiMTMwNWFjYjUtOWJmNS00YzE4LWE5ZDktOGEwNDNlMTc5OTcwIiwidCI6IjU4YTQyZWIyLWY0NTctNGM3YS1hZjA2LWU5NDEzYTJiNDE0MCJ9
## Design Decisions and Context
The design of the dashboard takes into consideration the following factors:
- **User-Friendly Interface:** The dashboard is designed to be intuitive and user-friendly, allowing stakeholders at various levels to explore and interpret the data easily.
- **Interactivity:** Power BI's interactive features enable users to drill down into specific data points, filter information, and derive actionable insights.
- **Emphasis on Key Metrics:** The visualization prioritizes key performance indicators, such as Total profit, Average shipping time, Top five customers, and Total sales by category.
- **Aesthetics:** Careful consideration has been given to the visual aesthetics, ensuring clarity, and a cohesive design that facilitates information absorption.
## INSIGHTS
- The top five customers were Sean Miller, Tamara Chand, Raymond Buch, Tom Ashbrook, and Adrian Barton.
- Technology was the most profitable category with $145k in profit.

- Copiers were the most profitable sub-categories with $25,204k in profit.
- Consumer segment had the highest sales of the three with $406,400 in sales.
- California had the highest sales of $159,271 among other states.
- October 2016 recorded the highest profit during the entire period of four years with a profit of $11,708.
- The Average shipping period was four days. 
