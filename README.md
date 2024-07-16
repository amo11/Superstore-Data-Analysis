# Superstore-Data-Analysis

## Overview
This project aims to analyze sales performance by regions, states, cities, customer segments, products, shipment modes etc and provide insights to the business in order to make correct decision and improve the profitability of the store. 

## Intoduction
With constant advancement in the technology and increasing competition globally, the business decisions heavily rely on clear, concise and insightful data. To cope with the dynamic world, it’s crucial to understand the market demand and provide more value to customers by addressing their challenges/requirements. Hence, this project aims to analyze Superstore’s sales data with the use of Python and give meaningful insights using visualization in order to help management take correct decisions.

## Data collection
The study uses publicly available data from Kaggle portal [Superstore sales Data](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting).

The Superstore dataset contains below variables:
| <ins> Variables </ins> | <ins> Description </ins> |
| :-------: | :----------: |
|  Row ID  | A unique ID for each row |
| Order ID | Unique order ID for each customer |
| Order Date | Order Date of the product |
| Ship Date | Shipping Date of the Product |
| Ship Mode |  Shipping Mode specified by the Customer |
| Customer ID |  Unique ID to identify each Customer |
| Customer Name | Name of the Customer |
| Segment |  The segment where the Customer belongs |
| Country | Country of residence of the Customer |
| City | City of residence of of the Customer |
| State | State of residence of the Customer  |
| Postal Code | Postal Code of every Customer |
| Region | Region where the Customer belong |
| Product ID | Unique ID of the Product |
| Category | Category of the product ordered |
| Sub-Category | Sub-Category of the product ordered |
| Product Name | Name of the Product |
| Profit | Profit of the Product|
| Sales | Sales of the Product |

## Data preparation
The data contains 9800 rows with 1 row being the header and it has the data for 3 years starting from January 3, 2015 to December 30, 2018 (with reference to Order Date). 

There are 11 rows with null values in the column Postal Code. I have removed such rows to get clear and non-null data which leaves us with 9789 rows. Overall the data is quite clean, reliable and consistent as there are no duplicate values found. 

## Analysis
+ *Sales and Profit over the years*
