# Retail Sales Performance Dashboard | Power BI

<img width="1397" height="796" alt="dashboard-preview" src="https://github.com/user-attachments/assets/0ff42681-922c-42fa-abaf-8c52b2b15362" />


---

## 📌 Project Overview

This project presents an executive-level Retail Sales Performance Dashboard built using the Superstore dataset in Power BI.

The dashboard analyzes revenue growth, profitability distribution, and product-level performance to support data-driven business decisions. It is designed using a clean visual hierarchy and structured layout to reflect real-world executive reporting standards.

---

## 🎯 Business Objective

The objective of this dashboard is to:

- Monitor overall sales performance  
- Evaluate profit contribution across categories  
- Analyze margin efficiency  
- Identify high-performing products  
- Detect revenue–profit imbalances across sub-categories  

The focus is on transforming raw retail data into actionable business insights.

---

## 📊 Key Metrics

- **Total Sales**
- **Total Profit**
- **Profit Margin (%)**
- **Total Orders**

---

## 📈 Dashboard Structure

### 🔹 Executive KPI Overview
Top-level performance summary designed for quick strategic evaluation.

### 🔹 Monthly Sales Trend (2014–2017)
Primary analytical visual highlighting growth momentum and seasonal variations.

### 🔹 Revenue Distribution by Category
Breakdown of sales contribution across Technology, Furniture, and Office Supplies.

### 🔹 Category Profit Contribution
Comparison of profitability across major product categories.

### 🔹 Sub-Category Sales vs Profit Analysis
Scatter-based evaluation identifying:
- High revenue / high profit segments  
- High revenue / low margin segments  
- Underperforming areas  

### 🔹 Top 10 Most Profitable Products
Ranking of products by profit contribution to assess performance concentration.

---

## 🔍 Key Business Insights

- Technology generates the highest revenue and profit contribution.
- Furniture produces significant revenue but comparatively lower margins.
- Sales demonstrate consistent upward growth over the observed period.
- Profitability is concentrated among a limited number of products.
- Certain sub-categories generate strong sales but moderate profit margins, indicating optimization opportunities.

---

## 🛠 Technical Implementation

### Data Modeling
- Data transformed and structured within Power BI.
- Relationships maintained for accurate aggregation and reporting.

### DAX Measures Used

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

Total Orders =
DISTINCTCOUNT(Superstore[Order ID])
