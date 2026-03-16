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
# 

    
