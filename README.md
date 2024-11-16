# Sales-Insights

### OBJECTIVE

AtliQ Hardware is a company that sells hardware like PCs and mouse and wants to find insights on it sales made during the 
year 2017 and 2020

### PURPOSE

To unlock sales insights that are not visible before sales team for decision support & automate them to reduce manual time spent in data gathering

### GOAL 

Create a Power BI dashboard which helps to analyze sales by customer and markets, product performance through time to come up with strategies to optimize sales and increase revenue 


### SUCCESS CRITERIA

•Dashboard uncovering sales order insights with latest data available

•Sales team able to take better decisions & [prove 10% cost savings of total spend

•Sales Analysts stop data gathering manually in order to save 20% of their business time and reinvest its value added activity


### CONTRIBUTION AND ROLE

The dataset was a SQL file with 148395 rows which was imported to MySQL workbench consisting of sales schema with 5 tables - customers,products,markets,sales transations and date.

Basic data analyzing was carried out and imported into Power BI through MySQL database using server and database name and loaded into power query for ETL and basic data cleaning was done 

#### Data Cleaning and Transformation

•Checked for duplicate records and removed them.

•Verified and corrected data types for all columns.

•Filtered out negative values in the Sales column.

•Converted currency values from USD to INR 

#### Created DAX Measures

•Revenue

•Sales Quantity

•Revenue Contribution %: Calculated as (Revenue / Total Revenue across markets, customers, and products).

•Profit Margin

•Profit Margin %: (Profit Margin / Revenue) * 100.

•Profit Margin Contribution %

#### Dashboard Development

Created a Power BI dashboard with three main reports:

##### 1.Overview

•Showcased three KPIs: Revenue, Sales Quantity, and Total Profit Margin.

•Analyzed Top 5 Products and Top 5 Customers by revenue.

•Visualized revenue distribution by customer type using a Donut Chart.

•Included a Line Chart to track sales trends and opportunities over time.

##### 2.Customer and Market Analysis

•Evaluated market performance using key metrics such as Profit Margin, Profit Margin Contribution %, and Revenue Contribution %.

•Compared Current Year Revenue with Last Year Revenue.

##### 3.Product and Market Analysis

•Assessed product performance through Cost Price, Revenue, and Profit Margin.

•Conducted segmentation of markets and customer types based on Sales Quantity and Revenue.


### Insights from Dashboard: 

#### Delhi Performance:

-Delhi accounts for 54.65% of total revenue but has a low profit margin of 0.59%, indicating potential cost issues or pricing inefficiencies that result in a poor ROI.

-The highest-value customer in Delhi is Electricaksara Stores, yet they contribute a minimal profit margin of 0.35%.
Customers with Reduced Profit Margins:

-Customers such as Epic Stores, Insight, Electricalsquipo Stores, Synthetic, Integration Stores, and Expression have experienced declining profit margins. These customers may require price adjustments or renegotiations to improve profitability.

#### Bhubaneswar Performance:

-Bhubaneswar has low revenue but a remarkable profit margin of 10.48%, showcasing effective cost control or pricing strategies.

#### E-Commerce Growth:

-E-commerce sales revenue increased significantly from 33.34M in 2017 to 60.68M in 2020, highlighting a growing preference for online shopping.

#### Overall Sales Decline:

- sales dropped from 15.9M in 2019 to 7.9M in 2020, reflecting the impact of the pandemic on business performance.

#### Top-Selling Product:

-Product 113 is the best-performing product in Bhubaneswar, achieving a 29% profit margin, underscoring its profitability in the region.








