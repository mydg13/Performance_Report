# Performance_Report


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
Revenue, Profit & Profit Margin Analysis (2017–2018)
- Revenue & Profit Trend:
  Revenue and profit follow a similar pattern, with noticeable peaks in December and 3 first months of year (holiday season: Christmas, New Year).
  A moderate increase is observed between March and May, followed by a decline in August and September.

- Profit Margin Fluctuations:
    Profit margin shows an inverse trend compared to revenue.
    It peaked at 32.47% in August 2017 and gradually declined over time, stabilizing around 26-27% in mid to late 2018.
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis1.png)


### 4.2 Store 
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis2.png)
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis3.png)

Nearly 60% of stores (29 out of 50) are located in the Downtown area. On average, Airport stores generate the highest daily revenue at $708, surpassing the other three areas. Airports appear to be a promising location for new stores, but further analysis is needed.

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis4.png)
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis5.png)

### 4.3 Product 

Revenue Share Analysis (2017 → 2018):

- Art & Crafts: Increased significantly from 12.12% to 25.84%, more than doubling, indicating strong growth in demand.
- Electronics: Dropped notably from 19.25% to 11.58%, confirming the decline in sales observed earlier.
- Games: Decreased slightly from 16.42% to 14.34%, suggesting a shift in consumer interest towards other categories.
- Sports & Outdoors: Remained relatively stable (14.96% → 15.12%), showing no significant change.
- Toys: Declined from 37.25% to 33.12%, but still holds the largest share, reaffirming its critical role in total revenue.

🔹 Key Insight: The rapid growth of Art & Crafts and the decline in Electronics highlight shifting customer preferences, which could inform future business strategies.

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis6.png)

The $15 - $20 range generates the highest revenue ($2.38M), followed by $10 - $15 ($1.56M).

$0 - $5 has the highest profit margin (41%), while $30+ has the lowest (13%).

High revenue ≠ high profit margin: $20 - $25 has low revenue but a strong 36% margin.

Balancing sales volume and profit margin is key for maximizing profitability.

![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis7.png)






