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

![Data Modelling](https://github.com/mydg13/Performance_Report/blob/main/image/image0.png)

## 3. Performance Report

### 3.1 Revenue Performance

![Revenue Performance 1](https://github.com/mydg13/Performance_Report/blob/main/image/image1.png)

![Revenue Performance 2](https://github.com/mydg13/Performance_Report/blob/main/image/image2.png)


### 3.2 Stores Performance

![Stores Performance](https://github.com/mydg13/Performance_Report/blob/main/image/image3.png)

### 3.4 Products Performance

![Products Performance](https://github.com/mydg13/Performance_Report/blob/main/image/image4.png)
