# DS 8003 (Management of Big Data and Big Data Tools) Project
## Problem Definition:
The retail stores sell products to customers and they would like to retain their customers and make them buy more products for increased profitability. For this purpose, various marketing campaigns are also run, in addition to improved service delivery and better pricing. To know if the employed strategy is working, it is important to know that what elements of the strategy steer the business in right directions and which of them are not producing the desired output.
## Proposed Solution:
In this project, we propose make use of data analysis/science to get the solution to the problem mentioned above. In particular, we would like to get the answer to the following questions.
1. What are the characteristics of customers whose spending at the store is increasing?
2. What are the categories of the products that are seeing increased/decreased sales?
3. What are the most profitable categories of the products over time?
4. Are the marketing campaigns effective?
5. Which of the marketing campaigns was the most successful one?
6. What are the characteristics of customers who were attracted by each marketing campaign?
## Tools Used:
1. Apache Hadoop for storage
2. Spark/Hive for querying
3. Kibana for the visualization
## Dataset:
We use the open-sourced dataset, titled The Complete Journey, made available by dunhumby. The dataset contains household level, anonymized, transaction data (2500 households) including the demographics and marketing campaigns (30 campaigns). The transactional data include over 90 thousand products categorized in 44 departments. The dataset is available at https://www.kaggle.com/frtgnn/dunnhumby-the-complete-journey.
To evaluate the efficiency of marketing campaigns, we will use "HOUSEHOLD_KEY" to combine transaction data, demographics, campaigns and coupons datasets. Based on this, we can extract valuable customers and focus on analyzing the effectiveness of each campaign and coupon sent by comparing their behavior before and after purchase. In addition, we will consider causal dataset to exclude the effects of other occurring events.

## Group Members:
1. Akshdeep Kaler
2. Li Gong
