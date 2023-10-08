
# Business insight 360


## Project Overview
AtliQ Hardware Data Analytics Project

"Welcome to the AtliQ Hardware Data Analytics project repository! Here, we've harnessed the power of Power BI to equip AtliQ Hardware with the tools to make informed decisions, outperform competitors, and fuel growth across finance, sales, marketing, and supply chain management."
## Table of Contents
+ Introduction                                                                               
+ Tech Stacks                                                     
+ Business Terminology               
+ Company Background  
+ Dataset  
+ Dashboard
## Introduction

"AtliQ Hardware, a worldwide leader in computer and computer accessories sales, is embracing the potential of data analytics through Power BI. Our mission with this project is to address key inquiries from stakeholders in finance, sales, marketing, and supply chain management. This empowers us to maintain a competitive edge in the dynamic market arena."
## Tech Stacks
+ SQL 
+ Power BI  
+ Excel  
+ DAX Language  
+ DAX studio (for optimizing the report)
## Business Terninology
+ Gross Price: The total price of a product or service before any deductions, such as taxes or discounts, are applied.

+ Pre-Invoice Deductions: Deductions made from the gross price before an invoice is generated. These could include discounts, allowances, or other adjustments.

+ Post-Invoice Deductions: Deductions made after an invoice is generated. These deductions might involve returns, rebates, or adjustments that affect the final amount the customer pays.

+ Net Invoice Sale: The final amount after deducting both pre-invoice and post-invoice deductions from the gross price.

+ Gross Margin: The difference between the revenue generated from sales and the cost of goods sold (COGS). It indicates how much profit a company makes from its core business operations.

+ Net Sales: The total revenue generated from sales after deducting returns, allowances, and discounts.

+ Net Profit: The total profit a company earns after deducting all expenses, including COGS, operating expenses, and taxes, from its total revenue.

+ COGC (Cost of Goods Sold): The direct costs associated with producing the goods that a company sells. It includes the cost of raw materials, labor, and manufacturing overhead.

+ YTD (Year to Date): Refers to the period starting from the beginning of the current calendar year up to the present date. It's often used to analyze performance or financial metrics within a specific timeframe.

+ YTG (Year to Go): Refers to the remaining period in the current calendar year, starting from the present date and extending until the end of the year.

+ Direct: A sales channel where products are sold directly from the manufacturer or company to the end consumer without intermediaries.

+ Retailer: An entity that purchases products from manufacturers or wholesalers and sells them to consumers, often through physical or online stores.

+ Distributors: Entities that purchase products in bulk from manufacturers and then sell them to retailers or other businesses. They help bridge the gap between manufacturers and retailers.

+ Consumer: The end-user or customer who purchases and uses the products or services offered by a company.
## Company Background:
"AtliQ Hardware is a swiftly expanding company specializing in the sale of computers and computer accessories across three core channels:

Retailers
Direct Sales
Distributors
With a worldwide footprint, company has experienced substantial growth in its business operations in recent years."

To secure our position in the industry, AtliQ Hardware recognizes the imperative need to build company's own analytics team. This team will be instrumental in providing data-driven insights and facilitating future survival and success.

The project kick-off session will serve as a critical phase where we aim to gain clarity on the project's purpose, objectives, and address any lingering questions."
## Dataset
## Dimension Tables
## dim_customer :

+ Contains details of customers across markets and platforms.
+ 27 distinct markets.
+ 75 distinct customers.
+ 2 types of platforms: Brick & Mortar (Physical/offline store), E-commerce (Online Store).
+ Three channels: Retailer, Direct, and Distributors.
## dim_market :
+ Contains details of markets, sub-zones, and regions.
+ 27 distinct markets.
+ 7 sub-zones.
+ 4 regions: APAC, EU, NA, LATAM.
## dim_product :
+ Contains details of product divisions, categories, and variants.
+ Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, + Storage.
+ 14 different categories (e.g., Internal HDD, keyboard).
+ Different variants available for the same product.
## Fact Tables 
## fact_forecast_monthly :
+ Used for forecasting customer needs in advance.
+ Helps improve customer satisfaction and reduce warehouse storage costs.
+ Denormalized for analytical use.
+ Date of the month replaced by start date.
+ Columns include forecast quantity needed by the customer.
## fact_sales_monthly
+ Similar to fact_forecast_monthly with actual sold quantities.
## Additional Tables
### gdb056
+ freight_cost: Details of travel and other costs for each market by fiscal year.
+ gross_price: Details of gross prices with product code.
+ manufacturing_cost: Details of manufacturing costs with product code and year.
+ Pre_invoice_dedutions: Details of pre-invoice deduction percentages for each customer by year.
+ Post_invoice_deductions: Details of post-invoice and other deductions.
This dataset provides comprehensive information about customers, markets, products, and various costs. The dimension tables offer static data, while the fact tables provide transactional and forecasting insights. Analyzing this dataset can lead to valuable insights for optimizing sales, costs, and customer satisfaction.



## Data Model


![Data model 360](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Datamodel360.png
)

## Dashboard

![Home Page](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Home%20_page.png)

![Finance View](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Financeview.png)

![Sales View](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Sales%20view.png)

![Marketing View](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Marketing%20view.png)

![Supplychain View ](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Supplychain%20view.png)

![Executive View](https://github.com/JBPANDYA/Business-insights-360-PowerBI-Project/blob/main/business_insights_360_images/Executiv%20eview.png)

