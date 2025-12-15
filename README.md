# MySQL-Project-Quarterly-Business-Health-Assessment

# Project Overview
This project provides an in-depth data analysis for New-Wheels, a vehicle resale company. The CEO requested a quarterly report to assess the health of the business after noticing steadily dipping sales and critical customer feedback online.
As a data analyst, the goal was to use SQL to process order and customer data and identify the core reasons behind the drop in customer acquisition and sales performance.

# Quarterly Trend Analysis Table
This table consolidates the most important operational and financial metrics across the four quarters, clearly illustrating the business's downward spiral.

| Metric | Q1 Output | Q2 Output | Q3 Output | Q4 Output | Trend Summary | 
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Net Revenue** | $39.6M | $32.9M | $29.4M | $23.5M | Steadily declining | 
| **Total Orders** | 310 | 262 | 229 | 199 | Fewer customers are placing orders| 
| **Avg. Rating** (1-5) | 3.55 | 3.35 | 2.96 | 2.40 | Steadily worsening satisfaction | 
| **% Negative Feedback** | 22% | 29% | 41% | 60% | Dissatisfaction reached its peak|
| **Avg. Days to Ship** | 57.17 | 71.11 | 117.76 | 174.10 | Increase in delays| 


#  Key Analytical Findings
* **The Problem is Fulfillment:** The single biggest issue is the massive increase in shipping time. Average delivery time went from **57 days** in Q1 to **174 days** in Q4.
* **Customer Satisfaction Collapsed:** The average customer rating dropped from "Good" (**3.55**) in Q1 to "Bad" (**2.40**) in Q4. 
* **Sales are Accelerating Downward:** Revenue and order volume fell every quarter. The revenue decline accelerated in Q4, reaching a **-20.18%** drop quarter-over-quarter.
* **Discounts are Not a Factor:** The discount strategy is very consistent and low (0.58% to 0.64%) across all credit card types, suggesting discounts are **not driving** sales or payment choice.
* **Untapped Markets Exist:** Customer activity is focused in a few states like Texas and California. Many states, such as Vermont and Wyoming, have very low activity, showing potential for targeted expansion.
