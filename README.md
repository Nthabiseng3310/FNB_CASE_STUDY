
# FNB Sales Case Study – Sales, Pricing & Profitability Analysis

## 📊 Project Overview

This project is a sales analysis case study based on daily trading data for one product at a large retail store.

I started by understanding the business questions and planning the project using **Miro** and a **Gantt chart**. I then loaded and validated the sales data in **Databricks** and used **SQL** to calculate the main sales and profitability metrics.

The main focus of the analysis was to understand how the product's **price, sales volume and profitability** changed over time, especially during potential promotional periods.

The analysis also helped me understand how customers respond when the product price changes.

---

## 🎯 Business Objective

The main objective was to use the available sales data to answer the following questions:

* What is the daily selling price per unit?
* What is the average selling price of the product?
* What is the daily gross profit percentage?
* What is the gross profit percentage per unit?
* Which periods could be considered potential promotional periods?
* How sensitive is demand to price changes?
* Does selling at a promotional price improve the product's performance?
* What other useful insights can be identified from the data?


## 🛠️ Tools Used

* **Databricks** – data processing and analysis
* **SQL** – calculations and data transformation
* **Data Studio,Power BI,Google Sheets,Databricks and Lovable** – dashboard and visualisation
* **Miro** – project planning
* **Gantt Chart** – project timeline and task planning
* **GitHub** – project Submition

---

## 🔄 Project Process

I followed these main stages throughout the project:

### 1. Understanding the Business Problem

I first reviewed the case study and identified the questions that needed to be answered.

The focus was mainly on:

**Sales → Pricing → Quantity → Profitability → Promotions → Price Elasticity**

---

### 2. Project Planning

Before starting the analysis, I planned the work using **Miro** and **Gantt chart**.

This helped me break the project into smaller tasks and keep track of the analysis, dashboard development and final presentation.

---

### 3. Data Loading 

I loaded the sales data into **Databricks** and checked the values of the dataset before performing the calculations.

I used SQL to explore the data and make sure the required fields were available for the analysis.

---

### 4. Data Analysis Using SQL

I created calculations for the main metrics required by the case study.


## 💡 Key Findings

The analysis produced several important findings.

### 1. Customers were highly price-sensitive

The elasticity results indicate that relatively small changes in price were associated with significant changes in quantity sold during the selected periods.

### 2. Promotions increased sales volume

The selected promotional periods were associated with substantial increases in average daily quantity sold.

The largest increase occurred during Promotion 1, where quantity increased by approximately **365%** compared with its preceding baseline period.

### 3. Higher volume did not automatically mean higher profit

Although promotional pricing increased the number of units sold, the overall profitability of the product remained a concern.

The analysis showed that total cost of sales was higher than total sales over the full dataset.

### 4. Pricing and cost need to be considered together

Looking only at quantity sold could give an incomplete picture.

A promotion can generate more sales while still putting pressure on margins if the price reduction is too large or the cost structure is unfavourable.

---

## 📌 Overall Performance

Some of the main overall metrics from the analysis were:

| KPI                            |         Result |
| ------------------------------ | -------------: |
| Total Sales                    | **≈ R186.91M** |
| Total Cost of Sales            | **≈ R194.03M** |
| Gross Profit                   |  **≈ -R7.12M** |
| Overall Gross Margin           |   **≈ -3.81%** |
| Weighted Average Selling Price |   **≈ R35.40** |

The overall results indicate that the product generated significant sales volume, but the cost of sales was higher than the sales revenue, resulting in an overall gross loss.

---

## 📊 Dashboard

I created dashboards with different tools to make the results easier to understand.

The dashboards focuses on:

* Total Sales
* Total Cost of Sales
* Gross Profit
* Gross Margin %
* Quantity Sold
* Average Selling Price
* Daily Price Trend
* Daily Sales Trend
* Profitability Trend
* Promotional Period Analysis
* Price Elasticity

The purpose of the dashboards was to turn the SQL analysis into an easy-to-read visual reports that could support business discussions and decision-making.

---

## 🎯 Recommendations

Based on the analysis, my recommendation is **not simply to increase promotions**.

Instead, the business should:

1. **Optimise promotional pricing**
   Use the elasticity results to understand how much demand responds to price changes.

2. **Monitor profit as well as volume**
   Higher quantities sold should not be considered successful if the additional sales do not contribute positively to profit.

3. **Investigate the cost structure**
   Since the overall cost of sales exceeded sales, understanding and managing costs should be a priority.

4. **Evaluate promotions based on profitability**
   Promotions should be measured using both volume and margin.

5. **Use data to support pricing decisions**
   Historical price and quantity patterns can help the business make more informed pricing decisions.


## 📌 Conclusion

The analysis showed that customers were highly responsive to price changes, and the selected potential promotional periods were associated with significant increases in sales volume.

However, the overall product performance was loss-making, which means increasing sales volume alone is not enough.

My main conclusion is therefore:

> **Promotions can increase demand, but pricing and cost management need to work together to turn increased volume into sustainable profit.**


