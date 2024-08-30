# Coffee_Sales_Analysis_Using_Excel

## Project Overview

The Coffee Sales Analysis project is designed to provide actionable insights into the sales performance of various coffee products over time. By analyzing a comprehensive dataset, the project highlights key trends in customer preferences, regional sales distribution, and product performance.

A central feature of this project is an interactive dashboard that visualizes coffee sales data from 2019 to 2022. The dashboard allows users to filter sales by different attributes, such as coffee type, roast type, size, and the use of loyalty cards. It also provides a timeline to examine sales trends across different months and years.

### Key components of the dashboard include:

   - **Sales Distribution Over Time**: A line chart that shows how sales fluctuate over different periods, helping identify patterns and peak sales times.
   - **Total Sales by Country**: A bar chart that breaks down sales by country, offering insights into regional performance.
   - **Top 5 Customers**: A list of the top customers based on total sales, which can be used to identify key customer segments.

## Dataset Description

The datasets utilized in this Coffee Sales Analysis project provides a detailed account of sales transactions over a period of several years.

There are three datasets used in this project:

**ORDERS**: Columns includes in orders dataset are as follows
- Order ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Customer Name
- Email
- Country
- Coffee Type
- Roast Type
- Size
- Unit Price
- Sales
- Loyalty Card

**CUSTOMERS**: Columns includes in customers dataset are as follows
- Customer ID
- Customer Name
- Email
- Phone Number
- Address Line 1
- City
- Country
- Postcode
- Loyalty Card

**PRODUCTS**: Columns includes in products dataset are as follows
- Product ID
- Coffee Type
- Roast Type
- Size
- Unit Price
- Price per 100g
- Profit

**Data Merging**

In this project, the Orders table serves as the primary dataset, containing key sales transaction details. To enrich this table, customer-related information such as Customer Name, Email, and Country was extracted from the Customers table. Similarly, product-related details, including Coffee Type, Roast Type, Size, and Unit Price, were sourced from the Products table. The integration of these details into the Orders table was accomplished using the INDEX and MATCH functions, allowing for seamless data merging and ensuring a comprehensive analysis.

## Dashboard Description

![dashboard of coffee sales analysis](https://github.com/PriyanshuG007/Coffee_Sales_Analysis_Using_Excel/blob/main/Dashboard_Screenshot.png?raw=true)

This dashboard provides a comprehensive overview of coffee sales performance over time. It includes various visualizations that help analyze sales trends, customer behavior, and sales distribution across different countries and roast types.

### Key Metrics and Visualizations

- **Sales Distribution Over Time**: A line chart shows sales trends over the years 2019 to 2022, broken down by roast type (Ara, Ex, Rob). This visualization helps identify seasonal patterns and overall sales growth.
 
- **Total Sales by Country**: A bar chart displays the total sales for the top three countries: the United States, Ireland, and the United Kingdom. This provides a quick comparison of sales performance in different regions.
  
- **Top 5 Customers**: A table lists the top five customers by total sales, along with their purchase amounts. This information is valuable for identifying high-value customers and tailoring marketing efforts.
 
- **Filters**: Slicers for Order Date, Size, Roast Type, and Loyalty Card allow users to filter the data and analyze specific segments. For example, users can view sales for a particular roast type or customer loyalty status.
  
