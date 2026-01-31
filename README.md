📊 Business Sales Analysis & Profitability Insights
📌 Project Overview

This project analyzes business sales data to understand revenue patterns, profitability drivers, and loss-making segments across product categories, regions, and sales channels. The goal is to identify key issues affecting profitability and provide data-driven business recommendations.

🎯 Objectives

Analyze sales performance across multiple dimensions

Identify loss-making categories and regions

Understand the impact of discounts on profitability

Provide actionable recommendations to improve business outcomes

🗂️ Dataset Description

The dataset contains 1,000 sales records with the following features:

Product and transaction details

Sales representatives and regions

Pricing, cost, quantity, and discounts

Customer type and sales channel

Note:
Sales_Amount was not used for revenue calculation as it did not reliably reflect discounts. Revenue was recomputed using pricing logic.

🧮 Revenue & Profit Calculation

Revenue was calculated as:

Total Revenue = Unit_Price × Quantity_Sold × (1 − Discount)


Profit was calculated as:

Profit = Total Revenue − (Unit_Cost × Quantity_Sold)

📈 Key Analyses Performed

Revenue and profit analysis by product category

Profitability analysis by region and sales channel

Discount vs profit correlation analysis

Visualization of loss patterns across segments

🔑 Key Findings

All product categories are operating at a loss, indicating systemic pricing or cost issues.

Electronics shows the least loss among categories.

Clothing and Furniture incur the highest losses.

Retail sales channel performs better than Online in terms of lower losses.

Higher discounts are strongly associated with increased losses.

💡 Business Recommendations

Re-evaluate pricing strategies, especially for Clothing and Furniture.

Introduce minimum pricing thresholds to avoid selling near or below cost.

Optimize discount policies by setting upper discount limits.

Improve cost efficiency in online sales channels.

Perform controlled experiments (A/B testing) on discount levels.

🔮 Future Work

Build predictive models to estimate profit based on pricing and discounts

Perform customer segmentation for targeted strategies

Analyze seasonal trends using time-series methods

Deploy analysis using dashboards or APIs

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

👤 Author

Ammar Tanveer
BS Statistics | Aspiring Data Scientist
📍 Pakistan
