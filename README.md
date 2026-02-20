# Retail Sales Performance Dashboard | Power BI

("C:\Users\eldho\OneDrive\Pictures\Screenshots 1\dashboard-preview.png")

---

## 📌 Project Overview

This project presents an executive-level Retail Sales Performance Dashboard built using the Superstore dataset in Power BI.

The dashboard analyzes revenue growth, profitability distribution, and product-level performance to support data-driven business decisions. It is structured using a clean visual hierarchy and minimal design clutter to reflect real-world executive reporting standards.

---

## 🎯 Business Objective

The objective of this dashboard is to:

* Monitor overall sales performance
* Analyze profit contribution across categories
* Evaluate margin efficiency
* Identify high-performing products
* Detect revenue–profit imbalances across sub-categories

The focus is on translating raw data into clear business insights.

---

## 📊 Key Metrics

* **Total Sales**
* **Total Profit**
* **Profit Margin (%)**
* **Total Orders**

---

## 📈 Dashboard Structure

### 🔹 Executive KPI Overview

Top-level summary designed for quick strategic review.

### 🔹 Monthly Sales Trend (2014–2017)

Primary analytical visual highlighting growth momentum and sales fluctuations over time.

### 🔹 Revenue Distribution by Category

Compares sales contribution across Technology, Furniture, and Office Supplies.

### 🔹 Category Profit Contribution

Highlights profitability differences across product categories.

### 🔹 Sub-Category Sales vs Profit Analysis

Scatter-based analysis identifying:

* High revenue / high profit segments
* High revenue / low margin segments
* Underperforming areas

### 🔹 Top 10 Most Profitable Products

Ranks products based on profit contribution to evaluate performance concentration.

---

## 🔍 Key Business Insights

* Technology generates the highest revenue and profit contribution.
* Furniture contributes substantial revenue but relatively lower margins.
* Sales show consistent growth over the observed period.
* Profitability is concentrated among a limited number of products.
* Certain sub-categories generate strong sales but moderate profitability, indicating margin optimization opportunities.

---

## 🛠 Technical Implementation

### Data Modeling

* Dataset transformed within Power BI.
* Measures created using DAX for KPI calculations.
* Clean relationship structure maintained for accurate aggregation.

### DAX Measures Used

```DAX
Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

Total Orders =
DISTINCTCOUNT(Superstore[Order ID])
```

---

## 🎨 Design Principles Applied

* Clear visual hierarchy (trend emphasized as core story)
* Balanced layout structure
* Reduced visual noise (minimal gridlines)
* Consistent spacing and alignment
* Executive-style reporting format

---

## 🚀 Skills Demonstrated

* Business Intelligence Reporting
* Data Modeling
* DAX Calculations
* Profitability Analysis
* Executive Dashboard Design
* Data Storytelling


