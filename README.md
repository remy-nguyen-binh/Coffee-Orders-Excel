
Introduction
This project aims to provide insights into sales trends, focusing on different types of coffee, geographic distribution, top customers, and loyalty card usage. 

Over these four years, we will examine monthly and yearly sales performance, identify popular coffee categories, and assess sales across various countries to pinpoint key markets and emerging opportunities. 

Additionally, we will profile the top five customers by purchase volume, analyze their buying patterns, and evaluate the impact of our loyalty card program on sales and customer retention. Through this analysis, we aim to identify potential growth areas, optimize our product offerings, and develop targeted marketing strategies to enhance customer engagement and drive business success.

Methods

Gathering data

1- Connecting Customer Data with XLOOKUP function to match the Customer ID from the Customers table with the Customer ID in the Orders table in order to to bring in customer-specific details such as Customer Email.


2- Connecting Product Data by using XLOOKUP function to match the Product ID in the Orders table with the Product ID in the Products table and retrieve product-related details such as Coffee Type, Size, Roast Type, and Unit Price.

Transforming data

After gathering and connecting the data from the Orders, Customers, and Products tables, the next step is to transform the data for better clarity and analysis. One essential transformation is standardizing the coffee type names. By converting shorthand notations to their full names, we can ensure consistency and improve readability. 

Formatting data

Next, I focused on formatting the data to ensure clarity and consistency, particularly for stakeholders in Asia. First, I changed the date format from month/day/year to day/month/year. To do this, I selected the date column, right-clicked to choose "Format Cells," navigated to the "Number" tab, selected "Custom," and entered the format code dd/mm/yyyy. Next, I formatted the size values by appending "kg" to each number for clarity. I selected the size column and used a formula to add "kg" to each value, converting, for example, "1" to "1 kg." Lastly, I formatted the unit prices to include the currency symbol "$." I selected the unit price column and used a formula to format the prices, converting, for example, "8.95" to "$8.95." These formatting changes ensure the data is presented clearly and is easily understandable for our stakeholders.

Next, I checked for duplicates in the data to ensure there were no redundant entries. After verifying and removing any duplicates, I addressed missing data by transforming any blank cells into "N/A" for clarity. Finally, I used the shortcut CTRL + T to convert the dataset into a table format. This step makes the data easier to manage and analyze, as it allows for filtering and sorting.

Data Analysis

I build pivot tables in order to have an overall look at the coffee orders data then build a excel dahsboard.

Recommendations

1- Focus on Top Sales Countries: Direct marketing efforts towards countries with high sales.

2- Optimize Product Selection: Tailor product offerings based on popular items to meet customer demand effectively.

3- Personalize Customer Engagement: Use insights from top customers to tailor marketing and loyalty programs for better engagement.

4- Encourage Loyalty Card Use: Promote loyalty card adoption to boost customer retention and repeat purchases.

4- Stay Agile: Continuously monitor sales trends and adapt strategies accordingly to remain competitive in the market.



