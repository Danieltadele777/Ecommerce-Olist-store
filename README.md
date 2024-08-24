# E-commerce Digital Analysis
In this project, I conducted an in-depth analysis of the **Brazilian E-Commerce company**, which includes detailed records of **100,000 orders** made between 2016 and 2018 across various **online marketplaces in Brazil**. This analysis provides a comprehensive view of the Brazilian e-commerce landscape, capturing a wide range of variables such as order status, pricing, payment methods, freight logistics, customer demographics, product characteristics, and customer reviews.

This analysis aims to extract actionable insights that can help understand customer behavior, optimize logistics, and improve overall e-commerce performance!

## Used KPIs
**Order Volume**: 
- Total Orders: The total number of orders placed during the period.
- Orders per Month/Quarter: Tracking the order trends over time.

**Revenue Metrics**:
- Total Revenue: Sum of the revenue generated from all orders.
- Average Order Value (AOV): Average revenue per order, calculated as total revenue divided by the number of orders.
- Revenue by Product Category: Breakdown of revenue by different product categories.

**Customer Metrics**:
- Customer Lifetime Value (CLV)
- Repeat Purchase Rate
- Customer Acquisition Cost (CAC)

**Payment Performance**:
- Payment Method Distribution: The percentage of transactions made using different payment methods (e.g., credit card, debit card, voucher).
- Payment Approval Rate: The percentage of orders where payment was successfully completed.
- Average Payment Value: Average amount paid per order across all payment methods.

**Logistics and Delivery Metrics**:
- Average Delivery Time: The average number of days from order confirmation to delivery.
- Freight Cost per Order: Average shipping cost associated with each order.
- Delivery Success Rate: Percentage of orders delivered successfully on the first attempt.
- Late Delivery Rate: Percentage of orders that were delivered later than the promised delivery date.

**Customer Satisfaction**:
- Average Review Score: Average rating provided by customers in their reviews.
- Percentage of 5-Star Reviews: Proportion of total reviews that are 5-star.
- Return Rate: Percentage of products that were returned by customers.

**Geographical Metrics**:
- Sales by Region: Total revenue generated from different geographical regions.
- Order Distribution by Region: Number of orders placed from different regions.
- Freight Cost by Region: Average shipping cost for orders delivered to different regions.

**Product Performance**:
- Top-Selling Products: Products with the highest sales volume.
- Inventory Turnover: Rate at which products are sold and replaced over time.
- Product Return Rate: Percentage of specific products that are returned.

## Table of contents
 - [Project Overview](#project-overview)
 - [Data Source](#data-source)
 - [Tools Used](#tools-used)
 - [Data cleaning](#data-cleaning)
 - [Exploratory data analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Findings](#findings)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
 - [Tableau visualization](tableau-visualization)
 - [References](#references)

### [Project Overview]()

By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company´s performance. 

### [Data Source]()

The data source used for this analysis is 'Brazilian E-Commerce Public Dataset by Olist: Kaggle. The site also provided detailed information about join keys and data schemas. 

### [Tools Used]()
- Excel: Primary data cleaning
- SQL: Google BigQuery for data cleaning and transformation
- Panda: for data cleaning, inspection, and analysis
- Tableau: Visualization

### [Data cleaning]()
In the initial data preparation phase I performed the following tasks:
- Data loading and inspection
- Handling missing values and duplicates
- Data cleaning and formatting

### [Exploratory data analysis]()
In this analysis, I explored key questions to gain insights into e-commerce performance and customer behavior:

- How did order volume and revenue evolve over time? Is there any seasonality? What are the peak sales periods?
- What are the patterns in payment methods and their impact on sales?
- What are the main drivers of delivery performance?
- Which product categories and attributes are the most popular?
- What are the key customer demographics and behavior patterns?
- How do customer reviews correlate with product performance?
- What are the trends in customer retention and repeat purchases?
- Did delivery performance or customer behavior vary by region?
- What is the overall sales trend?
- Which products are top sellers?
- Which products are sold in high quantities?
- Which seller sold the most?
- Which products received low reviews?
- Which products received high reviews?
- Which products generated the highest revenue?

### [Data Analysis]()
 For data analysis and cleaning, I used SQL and Panda. 

### [Findings]()

Based on the findings the following insight was generated:
1. Sales Trends and Seasonality: Holiday Peaks: The significant sales peak during the holiday season highlights the importance of seasonal promotions and inventory planning. The reduction in sales towards the end of 2018 may indicate a need for improved post-holiday strategies or adjustments in inventory management.

2. Revenue by Category: Health and Beauty Dominance: The Health and Beauty category's contribution of 14.59% to total revenue underscores its popularity. This category’s performance suggests that investing in marketing and promotions for these products could further boost sales.

3. Gift Watches: With 13.20% of the total revenue, Gift Watches also play a significant role. Consider exploring opportunities for expanding this category or introducing related products to capitalize on its success.

4. Delivery Performance: Ahead of Expectations: The company’s ability to deliver 54.51% ahead of expected delivery times is impressive and could be a key competitive advantage. Emphasizing this performance in marketing materials could enhance customer satisfaction and attract new customers.

5. Top Seller Performance: Seller ID 399,322,315: This seller's significant sales volume suggests they are a major contributor to overall revenue. It may be beneficial to analyze their strategies and practices to identify best practices that could be replicated across other sellers.

6. Top Rated Sellers: Sao Paulo Excellence: Four out of the top ten five-star rated sellers located in Sao Paulo indicate a strong market presence in this region. There may be regional factors contributing to their high ratings that could be leveraged in other regions.

### [Recommendations]()
Based on the analysis I recommend the following actions:

1. Optimize Inventory Management: Stock High-Demand Products: Ensure top-selling products, especially those in high-demand categories like Health and Beauty and Gift Watches, are adequately stocked, particularly during peak seasons such as the holidays. Implementing advanced forecasting models can help anticipate demand more accurately.

2. Review and Communicate Delivery Times: Adjust Expected Delivery Times: Given the company’s strong delivery performance, consider updating expected delivery times to more accurately reflect actual delivery capabilities. This adjustment can enhance customer trust and reduce dissatisfaction with delivery expectations.

3. Recognize and Reward Top Sellers: Incentivize Performance: Develop recognition programs or incentives for top-performing sellers, like Seller ID 399,322,315. Acknowledging and rewarding their efforts can boost motivation and set a benchmark for other sellers.

4. Address Negative Reviews: Investigate Low Ratings: For sellers with high numbers of one-star reviews, conduct a thorough review of their processes and customer service practices. Identify common issues and implement corrective actions to improve overall customer satisfaction.

5. Leverage Regional Strengths: Explore Sao Paulo Success: Investigate what makes sellers in Sao Paulo excel. It may involve factors like regional marketing strategies, customer service practices, or logistical efficiencies. Apply these insights to improve performance in other regions.

### [Limitations]()

- Customer Behavior Insights: Limited Customer Data: The dataset might not include detailed customer profiles or purchasing history beyond what is recorded, limiting the depth of behavioral analysis.
- Data Privacy and Ethical Considerations: Anonymization: The dataset is anonymized, which means some context about individual transactions or customer behavior may be lost, potentially limiting the depth of analysis.
- I had to remove all null values from the revenue column because they would have affected the accuracy of my conclusion. 
- In addition to that, I faced 601 products without any category. Because of limitations in the data provided, I wasn't able to add them to their respective categories.

### [Tableau visualization]()

[Dashboard](image)
<img width="1454" alt="Screenshot 2024-04-15 at 20 11 45" src="https://github.com/Danieltadele777/Ecommerce-Olist-store/assets/147874875/a2796f5f-35c4-418d-a99c-5121d4a35b51">
[Click here to Access the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/daniel.gebresenbet7026/viz/Moviesbygeneres/Olist)

### [References]()
- [Stack Overflow](www.stackoverflow.com)
