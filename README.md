# A Comprehensive Performance And User Demographic Analysis Of An Online Retail Store

## Project Overview

This project aims to derive actionable insights from a dataset of orders to address low profit margins and optimize revenue. By performing a sales performance analysis and RFM (Recency, Frequency, Monetary) analysis, we provide a comprehensive overview of key factors affecting revenue and profit. The findings will help shareholders and founders prioritize improvements on critical aspects of the business.
## Business Questions: 
- What are the key factors affecting our revenue and profit?
- Why is our profit so low compared to our revenue and total products sold?
- What defines our customers, which class each of them fall in, what are their favorite products, or times to buy
## Situation
- Only 12% of revenue is converted into gross profit (average profit margin of 12%).
- Profit margins vary significantly among products: some are highly profitable (up to 50%), while others incur losses (up to -200%).
## Dashboard Overview 
## Proposed Plans 
1. **Identify Key Sales Trends and Top-Performing Products**
   - **Approach 1: Optimize High-Contributing Products**
     - **Method:** Identify the top 20% of products contributing 80% of sales with a profit margin greater than the average profit margin (12%).
     - **Objective:** Focus on these products to enhance profitability, leveraging their significant contribution to overall sales.
     - **Action:** Examine patterns in sales and profitability to understand why these products perform well and apply these insights to other products.

   - **Approach 2: Address Non-Profitable Products**
     - **Method:** Identify products with a profit margin less than or equal to 0.
     - **Objective:** Investigate the reasons behind poor profitability and develop strategies to address the issues.
     - **Action:** Analyze factors such as production costs, pricing strategies, and market demand to improve the profitability of these products.
2. **Target the Right Audience**
   - **Method:** Identify the top 20% of customers contributing the most to revenue.
   - **Objective:** Understand their preferences and enhance customer loyalty.
   - **Action:** Discover their favorite products, implement targeted loyalty programs, and improve customer service to retain these valuable customers.
### Summary Of Insights 
### Proposed Solutions 
## Detailed Approach

1. **Dataset Overview**
   - **Description:** Overview of the dataset, including columns and data types (e.g., Order ID, Sales, Profit, Product Category, Customer ID).
   - **Objective:** Understand the structure and content of the data to ensure accurate analysis.

2. **Data Exploratory Analysis (EDA)**
   - **Summary Statistics:** Calculate basic statistics (mean, median, standard deviation) for sales, profit, and profit margins.
   - **Distribution Analysis:** Analyze the distribution of sales and profit margins to identify patterns and outliers.
   - **Correlation Analysis:** Examine correlations between sales, profit, and other features to identify key drivers of profitability.

3. **RFM Analysis**
   - **Recency:** Measure the time since the last purchase to identify recent vs. long-term customers.
   - **Frequency:** Calculate the number of purchases to segment customers based on purchasing behavior.
   - **Monetary:** Assess the total spending of customers to determine high-value customers.
4. ***K-means Clustering**:
   - Segment customer into 4 cohorts by RFM metrics: Best Customer, Loyal Customer, Potential Customer, and At Risk. Provide insights regarding purchasing behaviors of customer groups by identify what are their favorite products, and time to purchase. 
4. **Power BI Dashboards**
     1. **Sales Performance Dashboard**:
       A. **Dashboard Overview**
       B. **Charts**
   2. **Customer Behaviors Dashboard:**


### Optimization (In Progress):
- Implement Spark, and Python's API in Spark- Pyspark to transform, and query data with the Spark Sql
- Ultize AutoML to clean, preprocess data, and choose top 5 best fit model with it=> Print out the performance metrics of these models
## Getting Started

1. **Clone the Repository:**
   ```bash
   https://github.com/CeciliaDinh/Retail-Sales-Analysis-Visualization.git
