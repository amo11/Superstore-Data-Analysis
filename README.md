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
  Below table and the line graph (trend line) shows the sales and profit in USD. Staring with USD 480k, the sale has increased to USD 721k.There is a slight drop in the total sales in 2016 but it has steadily increased thereafter. The sale has been increased by 50% over the course of 3 years.
  
The profit has been steadily increased, even in the year 2016 where there is a decline in sales. The profit looks quite promising over the years.

<div align="center">![Sales and Profit over the year](https://github.com/user-attachments/assets/4a9e05aa-f118-4b28-93dd-8786819823d1)</div>

![Sales and Profit over the quarters](https://github.com/user-attachments/assets/f2bcf9f7-e139-466c-94fc-27d6425e4e04)

