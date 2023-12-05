# Sprocket-Central-Marketing-Analysis
![Premium Vector _ Drawing of the mountain bike competition hand draw](https://github.com/Emmanuelson321/Sprocket-Central-Analysis/assets/134542481/8cdd1b93-0cd8-4669-9a94-1739afa733a5)


## Introduction
Sprocket Central Pty Ltd. is a mid-sized company specializing in high-quality bikes and accessible cycling accessories for riders. Their marketing team is looking to boost business by analyzing their existing customer dataset to determine customer trends and behavior. They are also looking to expand into a new market.
We (KPMG) are helping to do this with a suitable marketing strategy.
The client (Sprocket Central Pty Ltd) provided KPMG with 3 data sets and 1 dataset of new customers for recommendation.

- Customer Demographic 
- Customer Addresses
- Transactions data in the past 3 months
- New Customers

## Problem Definition
Sprocket Central Pty Ltd. needs help with its customer and transaction data. The organization has a large dataset relating to its customers, but its team is unsure how to effectively analyze it to help optimize its marketing strategy. We helped by providing data-driven insights and actionable steps with the existing customer demography and sales transaction data to expand into a new market.

## Tools Used
The following are the tools used:
- Excel
- Tableau

## Skills demonstrated
- Data Cleaning
- Data quality assessment
- COUNTIFS, DATEDIF, VLOOK UP, IFS, and PROPER FUNCTION are some of the functions used.
- Pivot Table
- Table Calculation in Tableau
- Filters and Slicers in Tableau

## Data Quality Assessment
I did an in-depth exploration of the datasets with Excel, where I discovered several data quality issues needed for cleaning and transformation. The links to the data set are provided [here](https://cdn-assets.theforage.com/vinternship_modules/kpmg_data_analytics/KPMG_VI_New_raw_data_update_final.xlsx).

![KPMG dirt data](https://github.com/Emmanuelson321/Sprocket-Central-Analysis/assets/134542481/5706e868-a63e-4d41-b633-a45dfe2e474d)

The original customer demographic dataset contained 20,000 rows and 13 columns. There are 4002 distinct customers and 20,000 distinct transactions. The following are the steps I took for the data cleaning process:
- Inconsistent data type for the same attribute (e.g. numeric values for some fields and strings for others)
- Removed duplicate values
- Removed irrelevant columns such as the _Default column_
- Customer IDs 753 and 3790 are deceased and therefore not useful for the analysis

## Data wrangling and Modeling
After several data-cleaning processes to ensure validity, accuracy, and consistency, appropriate data transformations are made to ensure consistent data types for a given field. The date of birth column (D.O.B.) was transformed into 4 age brackets using the Tableau **table calculation** feature. I used Vlookup to look up the customer name in the transactions sheet based on the customer ID.

## Data Analysis and Visualization
The dashboard provides marketing insights and answers through an interactive report page. Here is the link to the [dashboard](https://public.tableau.com/shared/NWN4RCXC6?:display_count=n&:origin=viz_share_link)

![KPMG Dashboard](https://github.com/Emmanuelson321/Sprocket-Central-Analysis/assets/134542481/a1fa70f8-81da-45eb-9848-4f9952021b85)

The analysis chart below shows customers from manufacturing and financial services have been the major contributors to sales volume for the company.

![image](https://github.com/Emmanuelson321/Sprocket-Central-Marketing_Analysis/assets/134542481/84ba527c-753d-4de7-bb0e-bdf0fe917f86)

The chart presented below displays the distribution of customers by state and car ownership status. According to the chart, around 50% of customers in the NSW region do not own a car, which could be the reason for the high sales of bikes in that region.

![image](https://github.com/Emmanuelson321/Sprocket-Central-Marketing_Analysis/assets/134542481/e5fd2b03-c035-4b84-a8e8-e44cf9a83a57)

## Insights
- The most profitable customer segment for the company is the mass customer, which accounts for 50% of the total wealth segment.
- New South Wales customers contributed the most to the sales volume of the company.
- The age group of 28–50 is the most profitable, and new customers should be targeted from there.
- The female gender has the highest number of bike purchases and generates more profit for the company than its male counterpart.
- The WeareA2B brand is the most profitable, while Solex is the most purchased brand of bike.
The marketing company should focus on these customer segments to maximize profitability.

## Recommendation
To improve sales, optimize sustainability, and expand into a new market, these actions should be taken.
1. The mass customer in the wealth segment should be highly prioritized, especially in manufacturing, health, and financial services.
2. The female gender is the most highly valued customer and therefore should be prioritized.
3. Customers ranging between the ages of 28 and 50, and from New South Wales (NSW) should be sold to and considered.
4. New South Wales (NSW) is the most profitable region, while Victoria is the next-most profitable state. A marketing campaign can be launched in Victoria to create more brand awareness, which can improve customer engagement and drive sales.

Thank you for reading.
