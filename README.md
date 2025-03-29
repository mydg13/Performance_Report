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

Total sales and profit follow a similar trend: a slight rise from March to May, a drop in August and September, and a peak in December (holiday season: Christmas, New Year).

In contrast, the profit margin shows an inverse pattern, peaking at over 32% in August 2017 before gradually declining over time while remaining above 25%.
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis1.png)


### 4.2 Store 
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis2.png)
![Analysis Report](https://github.com/mydg13/Performance_Report/blob/main/image/image_analysis3.png)

Nearly 60% of stores (29 out of 50) are located in the Downtown area. On average, Airport stores generate the highest daily revenue at $708, surpassing the other three areas. Airports appear to be a promising location for new stores, but further analysis is needed.

