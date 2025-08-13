# Superstore-Dashboard
## Report

###  1. Project title: Superstore Sales Analytics:
Superstore Sales Insights Dashboard a dynamic, interactive data visualization tool 
built to explore Sales from a Superstore located in the US data focusing on Profit, total Sales, Products, customer segments and regions.

### 2. Description / Purpose:
The Superstore Analytics Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare orders Sales and Profit over the years staring from 2014 to 2017 across 49 sataes and observing the preformance of diffrent products categories, as well as diffrent customer segments.The main purpose of this report is to discover which products, regions, categories and customer segments they should target or avoid.

### 3. Tech method:
 
- Power BI Desktop – Main data visualization platform used for report creation.
- Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
- DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic, such as sales MoM (sales Month over Month), sales YoY (sales Year over Year).
- Data Modeling – Relationships established among tables (order_data, and customer_data) to enable cross-filtering and aggregation.
- File Format – .pbix for development and .png for dashboard previews.

### 4.Data Source:
Raw data was obtained form Kaggle [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

It containes 9994 rows and 24 columns

### 5. Insights:
#### Key questions:
- what are products ganerating better proit and what are the products that are preforming worst?
- which customer segments has higher profit and which customer segments has lower profit ?
- which regions and states has higher profit?

#### Results and suggestions:
- the store has exactly 1850 products during 2014 and 2017, and the product category that genraits the highest profit is technology and office supplies 145.45k and 122.49k respctivly. when we look deeper to understand which are the products that produce higher profit it is found that in the funal chart of the Top 10 Highest Profit Margin Products Ativa V4110MDD Micro-Cut Shredder, Zebra ZM400 Thermal Label Printer, Canon imageCLASS 2200 Advanced Copier has a profit margin 49%, 48%, and 40.91% respctivly which is considered the highest therefore the store should sale more of it. in the contrary, 
Eureka Disposable Bags for Sanitaire Vibra Groomer I Upright Vac, Bush Westfield Collection Bookcases, Dark Cherry Finish, Fully Assembled, and Euro Pro Shark Stick Mini Vacuum has profit margin -275%, -210%, and -190.71% respectivly which is considered the lowest profit margin as a result the store should resduce the number of units in the inventory to avoid profit loss.[Product Performance page](superstore_product-performance.png)

- the store should focus more in the sgemnet type customer and corporate since the genrated profit for them are 153.43k and 86.58k and lower offers for the home office segment.[Segment & States Performance page](superstore_sgement-performance.png)

- it appers that west and east regoins of the United Sataes has the highest profit of 108.42k and 91.52k respectivly, but the central and the south genrate the least profit, looking at the funal charts to discover even more which state to target and to avoid, California, New York, and Washington has the highest profit of $76,381.39, $74,038.55, and $33,402.65 resctivly. where as North Carolina, Texas, and Ohio has a profit of ($5,702.3028), ($7,840.6212), and ($9,239.9692) respectily.[Segment & States Performance page](superstore_sgement-performance.png)

####  Report of Key Visuals:
- Key KPIs top center total profit: $286.4k with a -12.45% MoM decrese in profit in the month of December 2017 compared to the month prior November 2017, Total seles: $2.3M with a -29.23% decrease in sales in the month of December 2017 compared to the month prior November 2017, total number of orders: 9994, and a profit margin of 12.47%.[overview page](Superstore_overview.png)
- As for the bar chart featuring the weekday of orders by profit and sales it shows that monday and friday counts for the highest number of sales and profit $248.94k in sales and $51.51k in profit for monday.To the right there is another bar chart it appers that overall the total profit and sales are increasing through out the years the total profit started at $49.54K in 2014 and ended at $93.44K in 2017 [overview page](Superstore_overview.png)


### 6.Screenshots of Dashborad:
[overview page](Superstore_overview.png)

[Product Performance page](superstore_product-performance.png)

[Segment & States Performance page](superstore_sgement-performance.png)

