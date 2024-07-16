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

![Sales and Profit over the year](https://github.com/user-attachments/assets/4a9e05aa-f118-4b28-93dd-8786819823d1)

![Sales over the yeras](https://github.com/user-attachments/assets/a388fe37-39fc-4e26-b7c1-3f0b04327f5a)


+ *Sales and Profit over the quarters*

It’s important to understand which time period is the most impactful throughout the year for the company. In this way, we would understand when are our best selling and profitable months.
  
In future, the company can implement highest resources, make most of the advertisements and implement new strategies during these months. Moreover, it will be easier to forecast the revenue for the upcoming years as we can anticipate similar patterns for sales and profit. Clearly, October, November and December are yielding highest revenue and profit to the company.

![Sales and Profit over the quarters](https://github.com/user-attachments/assets/12a32215-3dbf-4cf4-ae10-9c99f68ceef2)

+ *Most revenue collection and profit generation by Segment*

Out of three customer segments, Consumer segment brings the highest revenue as well as profit, followed by Corporate and Home Office in absolute value.

However, Profit Margin plays an important role in deciding which segment is the most profitable. Profit Margin is the ratio of Profit to Revenue and it indicates the profitability of any product. Surprisingly, Home Office brings most of the profit followed by Corporate and Consumer. 

![sales,profit and profit margin by segment](https://github.com/user-attachments/assets/2cddc3f6-cb18-43de-9722-afab468b27b2)

+ *Most revenue collection and profit generation by Region*

West has the highest sales overall. East is also looking promising. Hence, any new product can get most traction from west and east and it will be interesting to see the customer response to new products.

Similarly, West generates the most of the profit followed by East. However, it’s quite surprising to see that despite Central generating more revenue than south, it’s way behind South in terms of profit. Central region is quite alarming and greater attention has to be paid to this region to identify the reason of low profits.

![Sales by region](https://github.com/user-attachments/assets/4491f330-e171-4508-80d1-c16bee92b91d)

![Profit by region](https://github.com/user-attachments/assets/0eff7489-cfe3-426b-aa42-5dc75f556a07)

To reaffirm the above analysis, it’s interesting to have a look at profit margins. The figures validate above analysis. Profit margins are high in West, East and South in the order. Central has the lowest profit margin.

![sales, profit and profit margin by region](https://github.com/user-attachments/assets/a250b3fd-6e63-438f-9de1-dbbcdd2d5776)

+ *Top 10 States by Sales and Profits*

Below chart shows that the highest selling state is California contributing the most to the West to be the most profitable region followed by New York, Texas and so on.

![top 10 states by sales](https://github.com/user-attachments/assets/8595574e-275b-4b9d-af24-583a2587a299)

Looking at the profit, California secures the first position, followed by New Yok and Washington. Surprisingly, Texas could not make in top 10 despites generating third highest revenue overall. In depth analysis for Texas should be done in order to understand this erratic performance. 

![top 10 states by profit](https://github.com/user-attachments/assets/7d7f875c-3b97-4f45-a558-2d8712c77105)

![sale, profit and profit margin by top states](https://github.com/user-attachments/assets/5f49acdd-a8b8-4cde-9a9b-0cc8b0bbcbd6)

The above table gives brief idea on how the states are converting sales into profit. States such as Texas, Pennsylvania, Illinois and Ohio are loss making and they need immediate attention to improve it. 

+ *Bottom 10 States by Sales and Profits*

Below shows the Lowest selling state North Dakota followed by West Virginia and so on. Further analysis will be carried out on which products are getting sold in these states in order to understand the market demand better.

![bottom 10 state by sale](https://github.com/user-attachments/assets/fdfcd168-ecd8-47fb-abf6-dd8dc143490d)

![top 10 loss making states](https://github.com/user-attachments/assets/e45c7c18-7bde-4878-aec5-dd176e98fc95)

Most alarming state is Texas where we see highest loss despite generating $169k. It’s crucial to understand which products are making the loss over there. 

![sale, profit and profit margin by top states](https://github.com/user-attachments/assets/2bd82b33-610f-4544-8a35-16d89957fdc2)

Despite being in bottom 10 states by sales and profit in absolute terms, most of them have higher profitability than that of top 10 states by sales and profit. This gives us the indication to expand more in these states in order to increase profitability of the company.

+ *Top 10 Cities by Sales and Profits*

Below bar plot shows the top 10 cities by sales where New York city sits at the top followed by Los Angeles, Seattle. This is quite obvious as these are more populous cities than others making it bringing more sales to the company.

![top 10 cities by sale](https://github.com/user-attachments/assets/472e7a82-1ad1-49be-bf14-3f19165f8c23)

![top 10 cities by profit](https://github.com/user-attachments/assets/a17ee475-2559-4eeb-a7da-2f9f8c6be165)

Similarly, profit generation also follows the same pattern for top 4 cities. Philadelphia, Houston, Chicago being moderately high on sale could not make even moderate profits. It’s important to understand what is going wrong in these cities and how can we turn more profits out of sales.

+ *Bottom 10 Cities by Sales and Profits*

![bottom 10 cities by sale](https://github.com/user-attachments/assets/e9bd0394-3b29-4cd5-8465-f518735f2848)

There is no data available whether the lowest sales operating cities have physical Superstores available or the customers in such cities order the products online. This piece of data could have helped up calculate sales per square foot of a particular city which could help build strategies to improve the sales and profitability.

![top 10 loss making cities](https://github.com/user-attachments/assets/fff10131-1ee1-424a-9b0d-bbac69d5687d)

The above chart shows highest loss-making cities where 4 cities from Texas (Houston, San Antonio, Lancaster and Dallas) are making moderate to high loss.

+ *Sales and profit by Product Category*

It’s quite important to understand which product is bringing the highest revenue overall. Technology products are most sold followed by Furniture and Office Supplies.

![Revenue by category](https://github.com/user-attachments/assets/f3f260d5-e141-432c-88c6-87cbfe8b26d8)

![sale,profit and profit margin by category](https://github.com/user-attachments/assets/6c93b815-ae87-4b14-87a9-1410ec4853f6)

From Profit perspective, Technology still stands at first. However, Office Supplies yield more profit than Furniture despite the fact that the reverse is true for sales. It would be interesting to find why Furniture is low profitable and which sub category is yielding lowest profit. 

+ *Sales and profit by Product Sub Category*

Below snippet gives a good overview on which products are lucrative to the business and which products need attention. 
No wonder why Technology is at the top in terms of all the three attributes i.e. Sales, Profit and Profit margins. All the subcategories of Technology yield moderate to high sales as well as profits.

Secondly, though Office Supplies lags in terms of Sales from Furniture, only one sub category (Supplies) generate loss. A careful attention can convert it into profitable stream. 

Lastly, Furniture doing well in terms of sales but fails to convert it into profits. Chairs is profitable. But Tables and bookcases are responsible for losses. One of the reasons can be high operating expenses.  

![sale, profit and profit margin by subcategory](https://github.com/user-attachments/assets/147e439e-2ec9-4d00-81f2-2270feff8613)

+ *Sales by Ship Mode*

Below bar chart shows the total sale by ship mode: Standard class, First Class, Second class and Same Day.

Average days for each shipment class is also mentioned. 

![sale by shipmode](https://github.com/user-attachments/assets/4ea962bd-c66f-431f-9a4b-b10bda787fdb)

![avg days by shipmode](https://github.com/user-attachments/assets/e30a61ca-9826-47b9-a87c-5975369d58e9)

+ *Total customers and market penetration*

We have total 793 customers in United States. This figure along with market size (preferably bottom up approach) can suggest us to the intensity at which the market penetration should be done in order to capture the market.

## Conclusion


•	Sales and profits have shown steady increase (except sales in 2016) over 3 years and gained 50% more sales in 2018 compared to 2015. We should keep going in the upcoming years.





















