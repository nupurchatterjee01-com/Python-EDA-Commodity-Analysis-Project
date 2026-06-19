PROJECT TITLE:

Commodity  Analysis Using Python

PROJECT  DESCRIPTION:

This project analyzes commodity market data using Python to identify price trends, perform data cleaning and exploratory data
analysis (EDA),and generate meaningful insights through visualizations. The analysis helps understand market patterns and 
supports data-driven decision-making.


TOOLS USED:

.Database connection using SQLAlchemy

.Data Cleaning, Validation, and Table Joins using SQL

.Data Manipulation and Transformation using Pandas

.Exploratory Data Analysis (EDA)

.Commodity price trend analysis

.Data visualization using Matplotlib and Seaborn for Statistical Visualization 

.Microsoft PowerPoint (for project presentation)





1. Introduction:

The Commodity Price Analysis project focuses on analyzing commodity market data to identify price patterns, trends, and relationships among different variables. Using Python and SQL, the data was extracted, cleaned, analyzed, and visualized to generate insights that can support market understanding and data-driven decision-making.


2. Business Problem:
   
Commodity prices fluctuate due to various market factors, making it difficult to understand trends and patterns from raw data. The problem of this project were to:

a)Analyze commodity price movements and trends.

b)Identify relationships between different variables affecting prices.

c)Discover patterns and anomalies in the data.

d)Generate insights that can support business and market decisions.

3. Explain Charts and Key Visuals:

A. Univariate Analysis (One Variable)

Purpose: To understand the distribution and characteristics of a single variable.

Questions 1:
What is the overall distribution shape of our commodity retail prices & Do we have unusual or extreme pricing anomalies in our market data, and what is the typical boundary for a 'normal' commodity price?

Key Visual-
.Used Histogram with KDE to analyze the distribution of Retail_Price.
.Used Boxplot to detect outliers and extreme values.
.The distribution is right-skewed, with most prices concentrated at lower ranges.

Key Insights-

.Mean price (₹128.94) is much higher than median price (₹54), indicating positive skewness.
.Most commodities are low-priced, while a few products are extremely expensive.

Business Insights-

A High-Value "Long Tail": The long tail stretching out past 2,500 represents premium, bulk, or industrial non-food goods. They have a completely different price scale and account for low-volume, high-value revenue.


B. Bivariate Analysis (Two Variables)

Purpose: To study the relationship between two variables.

Categorical vs Numerical: Price by Category & State
Question 1: Do non-food items have a significantly higher or more volatile price range compared to food items?

Key Visual-

.Boxplot comparing Retail_Price across categories.

Key Insight- 

.Non-food items have a higher median price, while food items contain more extreme price outliers.

Business Insights-

Based on the boxplot comparing Food vs. Non-Food prices, here are the direct business insights:
Non-Food Items Have Higher Core Prices: The orange box (Non-Food) sits noticeably higher than the green box (Food). This tells us that the middle 50% of our non-food inventory naturally commands a higher baseline price than food staples.
Food Category Contains More Extreme Spikes: Look at the trail of outlier circles. Even though food is cheaper on average, it contains the absolute highest extreme pricing anomalies in the entire dataset.




C. Multivariate Analysis (More Than Two Variables)

Purpose: To understand interactions among multiple variables simultaneously.

Questions 1:

Which states have the Highest Average Prices across different categories?

Key Visuals-

.Created a pivot table and heatmap to compare average retail prices across different states and categories (Food and Non Food).

Key Insights-

.Significant price variations exist across states and categories.

.Several states show consistently higher average prices, especially in the Non-Food category.

.Regional differences influence commodity pricing patterns.


Business Insights-

This analysis helps identify states with higher average commodity prices across different categories. It highlights regional price variations and supports pricing, supply chain, and market planning decisions.






OVERALL KEY INSIGHTS:


(1)Commodity prices are highly unevenly distributed, with a small number of premium or industrial commodities having extremely high prices compared to most products. 

(2)A few major centres contribute a significant portion of commodity market data, making them key monitoring hubs.

(3)Commodity data reporting dropped significantly during the COVID-19 lockdown period. 

(4)Non-food commodities generally have higher average prices than food commodities. 

(5)Food commodities occasionally experience sharp price spikes despite lower average prices. 

(6)Northeastern states consistently show the highest average commodity prices due to logistical challenges. 

(7)Non-food commodity prices are more volatile and sensitive to market disruptions.



OVERALL BUSINESS IMPACT:


.Identified commodity price trends and regional price variations across categories.

.Highlighted high-value commodities and extreme price outliers for better market understanding.

.Helped identify premium and high-demand commodity segments.





PPT LINK:

https://github.com/nupurchatterjee01-com/Python-EDA-Commodity-Analysis-Project/blob/main/PYTHON%20EDA%20Commodity%20Proeject%20.pdf






