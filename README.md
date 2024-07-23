# Excel Project - Coffee Sales Study

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](tools)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Recommendations](#recommendations)



## Project Overview
This project aims to provide insights into sales trends, focusing on different types of coffee, geographic distribution, top customers, and loyalty card usage. 

Over these four years, we will examine monthly and yearly sales performance, identify popular coffee categories, and assess sales across various countries to pinpoint key markets and emerging opportunities. 

Additionally, we will profile the top five customers by purchase volume, analyze their buying patterns, and evaluate the impact of our loyalty card program on sales and customer retention. Through this analysis, we aim to identify potential growth areas, optimize our product offerings, and develop targeted marketing strategies to enhance customer engagement and drive business success.

## Data Source
You can download the raw excel file [here](https://github.com/mochen862/excel-project-coffee-sales)


## Tools
- Excel to clean and transform the data, then analyzed it with pivot tables and built a dashboard.

## Data Cleaning

### Gathering data
1. I used XLOOKUP to match Customer IDs between the Customers and Orders tables, adding customer emails.

2. I connected Product IDs from the Orders table to the Products table using XLOOKUP, retrieving details like Coffee Type, Size, Roast Type, and Unit Price.

### Transforming data

After gathering and connecting the data from the Orders, Customers, and Products tables, the next step is to transform the data for better clarity and analysis. One essential transformation is standardizing the coffee type names. By converting shorthand notations to their full names, we can ensure consistency and improve readability. 

 ### Formatting data

I formatted the data for clarity and consistency for our Asian stakeholders. I changed the date format to day/month/year, appended "kg" to size values, and added the "$" symbol to unit prices. I removed duplicates, transformed blank cells into "N/A," and converted the dataset into a table for easier management and analysis.

## Data Analysis

I build pivot tables in order to have an overall look at the coffee orders data then build a excel dahsboard.


## Recommendations

1- Focus on Top Sales Countries: Direct marketing efforts towards countries with high sales.

2- Optimize Product Selection: Tailor product offerings based on popular items to meet customer demand effectively.

3- Personalize Customer Engagement: Use insights from top customers to tailor marketing and loyalty programs for better engagement.

4- Encourage Loyalty Card Use: Promote loyalty card adoption to boost customer retention and repeat purchases.

4- Stay Agile: Continuously monitor sales trends and adapt strategies accordingly to remain competitive in the market.



