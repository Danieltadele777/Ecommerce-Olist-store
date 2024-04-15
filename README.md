# E-commerce Olist store sales analysis
## Detailed analysis of Brazilian Ecommerce store: 100k orders from 2016 to 2018
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
 - [References](#references)

### Project Overview 

This data analysis project aims to provide insights into the sales performance of an e-commerce company during the period of 2016 to 2018. By analyzing various aspects of the sales data, we seek to identify trends, make data driven recommendations, and gain a deeper understanding of the company´s performance. 

### Data Source

The data source used for this analysis is 'Brazilian E-Commerce Public Dataset by Olist: Kaggle'. The site also provided detailed information about join keys and data schemas. 

### Tools Used
- Excel: Primary data cleaning
- SQL: Google BigQuery for data claning and transformation
- Tableau: Visualization

### Data cleaning
In the initial data preparation phase I performed the following tasks:
1. Data loading and inspection
2. Handling missing values and duplicates
3. Data cleaning and formatting

### Exploratory data analysis
- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?
- Which prodcuts sold in high quantitiy?
- Which seller sold the most?
- Which products got low reviews?
- Which products got high reviews?
- Which products generated highest revenue?
- Orders seasonality?

### Data Analysis
Some of the SQL codes used. [detailed SQL codes attached here]()
```SQL
SELECT *
FROM
WHERE
```

Some of the Python codes used. [detailed Python codes attached here]()


### Findings
1. The analysis resulsts are summarized as follows:
2. The company sales have been steadily growind during the year 2016 and 2017, with a significant peak during the holiday season. During late 2018 the sales showed a minor reductions. 
3. Interms of revenue and sales health and beauty is the best performing category.
- Health and beauty catagory generated 1, 448, 730 (14.59% of the total revenue).
- Gift watches generated 1, 310, 893 (13.20% of the total revenue).
4. Interms of delivery performance, the company delivers way a head of expected delivery time by 54.51%.
5. Seller ID 399, 322, 315 sold quite significant amount of products during those years.
6. From top 10 five star rated sellers, four of them located in Sao Paulo.

### Recommendations
Based on the analysis I recommend the following actions:
1. Always make sure to have the top selling products in stock, especailly during holiday season.
2. Since the store delivery performance is astonishing, it might be neccssary to review the expected delivery time.
3. It might be neccssary to recognize the top sellers or recognize them.
4. Some sellers got a high amount of 1 star reviews. It might be neccssary to find out the reason and review the process.

### Limitations

- I had to remove all null values from the revenue column because they would have affected the accuracy of my conclusion. 
- In addition to that, I faced 601 products without any category. Because of limitations in the data provided, I wasn't able to add them to their respective categories.

### References
1. [Stack Overflow](www.stackoverflow.com)
2. 
