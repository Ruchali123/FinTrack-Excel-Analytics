# 📊 FinTrack: Smart Financial Analytics – Excel Project

## 🔹 Introduction

**FinTrack: Smart Financial Analytics** is an Excel-based project designed to convert raw financial data into **actionable insights**.
Using Excel features like **Pivot Tables, Pivot Charts, slicers, and timelines**, this project builds an **interactive financial dashboard** to analyze sales, profits, discounts, and trends across regions, products, and time periods.

---

## 🎯 Objectives

* Clean and prepare raw financial datasets.
* Build Pivot Tables to analyze **sales, costs, and profitability**.
* Create **interactive dashboards** with slicers and timelines.
* Detect **seasonality and year-over-year growth trends**.
* Assess the **impact of discounts** on revenue and profits.
* Improve **data storytelling** and decision-making skills.

---

## 📂 Dataset Overview

The dataset includes:

* **Sales, Costs, and Profits**
* **Countries & Market Segments**
* **Product Categories**
* **Discount details**
* **Date field for trend analysis**

🔗 Dataset: `Financial_Sample_Cleaned.xlsx`

---

## 🧹 Data Cleaning Process

To prepare the dataset for analysis, the following transformations were made:

1. **Date Breakdown** (from `Date` column):

   * `Year` → `=YEAR([@Date])`
   * `Month Number` → `=MONTH([@Date])`
   * `Month Name` → `=TEXT([@Date], "MMMM")`

2. **Standardization**:

   * Trimmed spaces in categorical fields (`Country`, `Segment`, `Product`).

3. **Handling Missing/Invalid Data**:

   * Replaced blanks in numeric fields with `0`.
   * Verified no negative discounts or inconsistent entries.

4. **Data Types Check**:

   * Dates formatted as Date
   * Currency fields formatted as Number with 2 decimals
   * Categories formatted as Text

📂 Final cleaned dataset: **`Financial_Sample_Cleaned.xlsx`**

---

## ❓ Problem Statement

The company wants to analyze **sales performance** across products, markets, and countries to answer:

* Which **products & segments** generate the highest revenue and profit?
* How do **sales trends** vary across countries and time?
* What is the **impact of discounts** on profitability?
* Are there **seasonal variations** in sales?

Extended goals:

* 📅 **Seasonality Detection**
* 📈 **Year-over-Year Performance**
* 💰 **Discount Trend Analysis**
* 🔮 **Sales Forecasting**

---

## 🔎 Methodology

1. **Data Cleaning & Preparation**
2. **Pivot Table Analysis** → Revenue, Profit, Discounts
3. **Visualization** → Bar, Line, Pie, and Column Charts
4. **Dashboard Design** → Slicers, Timelines, and Interactive Views
5. **Insights & Recommendations**

---

## 🛠 Features

* Cleaned dataset with **Year, Month Number, Month Name**
* Pivot Tables for multi-dimensional analysis
* Dynamic filters using slicers & timelines
* Interactive dashboard showcasing trends & insights
* Business-ready recommendations

---

## 📸 Dashboard Preview

<img width="1863" height="668" alt="dashboard_preview" src="https://github.com/user-attachments/assets/b5325c48-0049-418c-8adf-8d7429c54ac3" />

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open **`Financial_Sample_Cleaned.xlsx`** in Excel.
3. Explore the Pivot Tables & Dashboard.
4. Use **slicers and filters** to interact with the data.


