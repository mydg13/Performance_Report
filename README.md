# Performance_Report
---

1. [Dataset](#1-dataset)  
2. [Data Modelling](#2-data-modelling)  
3. [Performance Report](#3-performance-report)  
4. [Insight & Recommendation](#4-insight--recommendation)  
  
--- 

## 1. Dataset
The dataset, provided by Maven Analytics, includes three key tables:

- Products – 35 products sold at Maven Toys, with details on category, cost, and retail price.
- Stores – 50 store locations, including details on location, type, and opening date.
- Sales – Over 800,000 transactions (Jan 2017 – Sep 2018), tracking product sales per store and date.


#### `products.csv`
|**Field**|**Description**|
|-|-|
|Product_ID|Product ID|
|Product_Name|Product name|
|Product_Category|Product Category|
|Product_Cost|Product cost ($USD)|
|Product_Price|Product retail price ($USD)|

#### `stores.csv`
|**Field**|**Description**|
|-|-|
|Store_ID|Store ID|
|Store_Name|Store name|
|Store_City|City in Mexico where the store is located|
|Store_Location|Location in the city where the store is located|
|Store_Open_Date|Date when the store was opened|

#### `sales.csv`
|**Field**|**Description**|
|-|-|
|Sale_ID|Sale ID|
|Date|Date of the transaction|
|Store_ID|Store ID|
|Product_ID|Product ID|
|Units|Units sold|


## 2. Data Modelling
Create a date table spanning the earliest to the latest date in the sales data.

Establish one-to-many relationships between dimension tables and the fact table.

![Data Modelling](https://github.com/mydg13/Performance_Report/blob/main/image/image_report0.png)

## 3. Performance Report

### 3.1 Revenue Performance

![Revenue Performance 1](https://github.com/mydg13/Performance_Report/blob/main/image/image_report1.png)

![Revenue Performance 2](https://github.com/mydg13/Performance_Report/blob/main/image/image_report2.png)


### 3.2 Stores Performance

![Stores Performance](https://github.com/mydg13/Performance_Report/blob/main/image/image_report3.png)

### 3.4 Products Performance

![Products Performance](https://github.com/mydg13/Performance_Report/blob/main/image/image_report4.png)


## 4 . Insight & Recommendation 

### 4.1. Overall 
- Key Observations: : Revenue, Profit & Profit Margin Analysis (2017–2018)
  
     - Revenue & Profit Trend: Revenue and profit follow a similar pattern, with noticeable peaks in December and 3 first months of year (holiday season: Christmas, New Year). A moderate increase is observed between March and May, followed by a decline in August and September.
  
     - Profit Margin Fluctuations: Profit margin shows an inverse trend compared to revenue. It peaked at 32.47% in August 2017 and gradually declined over time, stabilizing around 26-27% in mid to late 2018.
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis1.png)

- Recommendations: While revenue and profit increased during peak seasons, the declining profit margin suggests rising costs or pricing adjustments. The company may need to analyze cost structures to maintain profitability.


### 4.2 Store 
- Key Observations:

     - Downtown stores dominate revenue (57.35%) and profit (56.51%) but have the lowest profit margin (25.82%).
  
     - Residential & Airport stores have the highest profit margins (~27%).
  
     - Cuidad de Mexico & Guadalajara are top-performing cities in revenue & profit.
  
     - Smaller cities (Saltillo, Xalapa) contribute less but still maintain profitability.

- Recommendations:
     - Expand in Downtown but optimize costs to improve margins.

     - Consider increasing presence in Residential & Airport areas for higher margins.

     - Invest in top cities (Cuidad de Mexico, Guadalajara, Monterrey) for stable growth.

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis2.png)



![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis4.png)
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis5.png)

### 4.3 Product 

- Key Observations:

     - Art & Crafts: Increased significantly from 12.12% to 25.84%, more than doubling, indicating strong growth in demand.
     - Electronics: Dropped notably from 19.25% to 11.58%, confirming the decline in sales observed earlier.
     - Games: Decreased slightly from 16.42% to 14.34%, suggesting a shift in consumer interest towards other categories.
     - Sports & Outdoors: Remained relatively stable (14.96% → 15.12%), showing no significant change.
     - Toys: Declined from 37.25% to 33.12%, but still holds the largest share, reaffirming its critical role in total revenue.

- Recommendations: The rapid growth of Art & Crafts and the decline in Electronics highlight shifting customer preferences, which could inform future business strategies.

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis6.png)

- Key Observations:
     - $0–$5: Low revenue but highest profit margin

     - $15–$20: High revenue but low margin (21%)

     - $30+: Lowest margin (13%) 

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis7.png)


Some recommendation : The company should diversify its product portfolio, focusing on the Electronics category due to its high profit margins. It should also analyze pricing strategies and the relationship between price, revenue, and profit to optimize overall performance.



