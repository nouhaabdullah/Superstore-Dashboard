# Superstore-Dashboard
## Report

###  1. Project Title: Superstore Sales Analytics:
Superstore Sales Insights Dashboard is a dynamic, interactive data visualization tool built to explore sales from a US-based Superstore.
The dashboard focuses on profit, total sales, products, customer segments, and regions.

### 2. Description / Purpose:
The Superstore Analytics Dashboard is a visually engaging Power BI report designed to help users explore and compare sales and profit from 2014 to 2017 across 49 states. It allows for observation of different product categories and customer segments. The main purpose is to identify which products, regions, categories, and customer segments to target or avoid.
### 3. Tech method:
 
- Power BI Desktop – Main data visualization platform used for report creation.
- Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
- DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic, such as sales MoM (Month over Month), sales YoY (Year over Year).
- Data Modeling – Relationships established among tables (order_data, and customer_data) to enable cross-filtering and aggregation.
- File Format – .pbix for development and .png for dashboard previews.

### 4.Data Source:
Raw data was obtained form Kaggle [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

It containes 9994 rows and 24 columns

### 5. Insights:
#### Key questions:
- What products generate better profit and which ones perform worst?
- Which customer segments have higher profit and which have lower profit?
- Which regions and states have higher profit?

#### Results and suggestions:
- The store carried 1,850 products between 2014 and 2017. Technology and office supplies generated the highest profits at $145.45k and $122.49k respectively. Looking deeper at individual products, the Top 10 Highest Profit Margin Products chart shows that Ativa V4110MDD Micro-Cut Shredder (49%), Zebra ZM400 Thermal Label Printer (48%), and Canon imageCLASS 2200 Advanced Copier (40.91%) have the highest profit margins. The store should sell more of these items. In contrast, Eureka Disposable Bags for Sanitaire Vibra Groomer I Upright Vac (-275%), Bush Westfield Collection Bookcases, Dark Cherry Finish, Fully Assembled (-210%), and Euro Pro Shark Stick Mini Vacuum (-190.71%) have the lowest profit margins. The store should reduce inventory of these items to avoid profit loss.[Product Performance page](superstore_product-performance.png)

- The store should focus more on the Customer and Corporate segments since they generated profits of $153.43k and $86.58k respectively, while offering fewer promotions to the Home Office segment.[Segment & States Performance page](superstore_sgement-performance.png)

- The West and East regions of the United States have the highest profits at $108.42k and $91.52k respectively, while the Central and South regions generate the least profit. Looking at individual states, California ($76,381.39), New York ($74,038.55), and Washington ($33,402.65) have the highest profits. Meanwhile, North Carolina (-$5,702.30), Texas (-$7,840.62), and Ohio (-$9,239.97) show losses.[Segment & States Performance page](superstore_sgement-performance.png)

####  Report of Key Visuals:
- Key KPIs (top center) show total profit: $286.4k with a 12.45% MoM decrease in profit in December 2017 compared to November 2017. Total sales: $2.3M with a 29.23% decrease in sales in December 2017 compared to November 2017. Total number of orders: 9,994, with a profit margin of 12.47%.[overview page](Superstore_overview.png)
- The bar chart featuring weekday orders by profit and sales shows that Monday and Friday account for the highest number of sales and profit—$248.94k in sales and $51.51k in profit for Monday. To the right, another bar chart shows that overall profit and sales increased throughout the years, with total profit growing from $49.54K in 2014 to $93.44K in 2017. [overview page](Superstore_overview.png)


### 6.Screenshots of Dashborad:
[overview page](Superstore_overview.png)

[Product Performance page](superstore_product-performance.png)

[Segment & States Performance page](superstore_sgement-performance.png)

