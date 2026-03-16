# Customer_behavior_analysis (Interactive Dashboard creation using MS Excel)
# Project Objective
The goal of this project is to analyze customer shopping behavior across product categories to uncover patterns in purchasing habits, revenue distribution, customer segmentation, and subscription impact. The insights derived help businesses make data-driven decisions to improve marketing strategies, boost revenue, and enhance customer retention.
#  Dataset Used
File: customer_shopping_behavior.csv,  3,900 records, 18 features, column descriptions table.
#  Questions / KPIs
The following key business questions were explored:
1) What is the total revenue split between male and female customers?
2) Which product categories generate the highest revenue and sales volume?
3) What are the top 5 products by average customer review rating?
4) How are customers segmented — new, returning, or loyal?
5) What is the impact of subscription status on average spend and total revenue?
6) Which age group contributes the most to revenue and sales?
7) Which products are most frequently discounted?
8) Does shipping preference influence purchase amount?
9) How many repeat buyers (subscribers with more than 5 purchases) exist?
# Process
1. Data Collection
Loaded the raw CSV dataset containing 3,900 customer transaction records.

2. Data Cleaning & Preparation
Identified and imputed 37 missing values in the Review Rating column.
Standardized column data types (numeric, categorical).
Created derived fields: Age Group buckets (Young Adult, Adult, Middle-aged, Senior), Customer Segment (New / Returning / Loyal) based on Previous Purchases.

3. Exploratory Data Analysis (EDA)
Analyzed revenue by gender, product category, age group, and subscription status.
Evaluated rating distribution across product items.
Investigated the effect of discount and promo code usage on purchase behavior.

4. Dashboard Development
Built an interactive Power BI dashboard (customer_behaviour_dashboard.pbix) with dynamic filters for gender, season, category, and subscription status.

5. Insight Extraction & Recommendations
Synthesized findings into actionable business recommendations.
# Dashboard
The Power BI dashboard (customer_behaviour_dashboard.pbix) includes Donut/pie chart showing male (73%) vs. female (27%) revenue split, Bar chart of revenue and sales volume across Clothing, Accessories, Footwear, and Outerwear, Ranked list of top 5 items by average review rating, Count breakdown of New, Returning, and Loyal customers, Comparison of avg spend and total revenue for subscribers vs. non-subscribers, Revenue and sales contribution by age group.
# Project Insights
1) Male customers dominate revenue — Males account for 73% ($157,890) of total revenue vs. 27% ($75,191) for females.
2) Clothing is the top category — With $100K revenue and 1,800 sales, it far outperforms other categories.
3) Accessories rank second — Generating $75K revenue across 1,200 sales.
4) Gloves are the highest-rated product — With an average rating of 3.86, followed by Sandals (3.84) and Boots (3.82).
5) Most customers are loyal — 3,116 out of 3,900 customers are classified as loyal, with only 83 being new.
6) Non-subscribers drive more revenue — 2,847 non-subscribers contribute $170,436 vs. $62,645 from 1,053 subscribers.
7) Subscription avg spend is slightly lower — Subscribers spend $59.49 on average vs. $59.87 for non-subscribers.
8) Young Adults are the top buyers — The 27% Young Adult segment generates $45K revenue and 1,000 sales.
9) Express shipping correlates with higher spend — Customers choosing express shipping tend to spend more per transaction.
10) Discount-heavy products include Hats, Sneakers, and Coats — Frequent discounting may be impacting margins.
11) 958 subscribers are high-frequency buyers — These customers made more than 5 purchases, indicating strong loyalty potential.
#  Conclusion
This analysis reveals that the business is largely driven by male customers, clothing purchases, and a loyal customer base. While non-subscribers make up the majority of revenue, the 958 high-frequency subscribers represent a valuable retention asset. The low new-customer count (83) signals a need for better customer acquisition strategies.

    
