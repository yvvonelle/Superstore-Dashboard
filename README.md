# 🛒 Superstore Sales Performance: Executive Power BI Report

## 📌 Project Overview
[cite_start]This project transforms  Superstore transactional data into a high-impact interactive dashboard[cite: 5, 15]. [cite_start]The objective was to move beyond basic reporting and uncover the "story" within the data: identifying which products drive genuine profit, how regional trends shift, and the specific threshold where discounting begins to destroy value[cite: 5, 7, 12].

[cite_start]This analysis provides a data-driven look at retail health, offering critical insights for inventory optimization and regional pricing strategies[cite: 5, 6].

---

## 🏗️ Data Architecture & ETL
To ensure high-performance filtering and data integrity, the project followed a structured technical pipeline:
* [cite_start]**Data Cleaning (Python):** Used **pandas** to remove duplicate records and verify the integrity of all financial columns[cite: 23, 24, 27].
* [cite_start]**Feature Engineering:** Standardized all temporal data into datetime objects and derived a custom **Ship Duration** column to track fulfillment efficiency[cite: 25, 26].
* [cite_start]**DAX Modeling:** Developed a dedicated **Measures Table** to house complex logic, including YoY Sales Growth, Profit Margin %, and dynamic Product Rankings[cite: 33, 34].
* [cite_start]**Refined Schema:** Organized the dataset to support seamless cross-highlighting across four distinct analytical zones[cite: 30].

---

## 📊 Dashboard Architecture
[cite_start]The report is designed as a single-page executive summary divided into four logical pillars[cite: 30]:

### 🟦 KPI Performance Strip
[cite_start]**Goal:** Establish an immediate baseline of organizational health[cite: 31].
* [cite_start]**Visuals:** KPI Cards for Total Sales, Profit, and Average Discount[cite: 31].
* [cite_start]**Logic:** Integrated **Year-over-Year (YoY) Sales Growth** with conditional arrows to show growth trends at a glance[cite: 31, 34].

### 🟩 Category & Sub-Category Analysis
[cite_start]**Goal:** Identify which business segments are "hero" drivers versus "loss" centers[cite: 31].
* [cite_start]**Visuals:** Horizontal Bar Charts with **conditional formatting** (Red) to highlight unprofitable sub-categories[cite: 31].
* [cite_start]**Logic:** Analyzes the performance of Technology drivers versus loss-heavy Furniture items like Tables and Bookcases[cite: 38, 39, 40].

### 🟨 Discounting & Profit Correlation
[cite_start]**Goal:** Quantify the financial friction caused by aggressive pricing[cite: 31].
* [cite_start]**Visuals:** **Scatter Chart** with a trend line to map the relationship between Discount % and Net Profit[cite: 31].
* [cite_start]**Logic:** Identifies the "danger zone" where discounts of **30% or higher** lead to consistent losses[cite: 42, 43].

### 🟥 Geographic & Customer Value
[cite_start]**Goal:** Optimize regional resource allocation and identify true high-value customers[cite: 31].
* [cite_start]**Visuals:** **Filled Map** (Color saturation = Sales) and a Top Customer Table[cite: 31].
* [cite_start]**Logic:** Highlights the gap between high-revenue customers and high-profit customers to guide loyalty strategies[cite: 46, 48].

---

## 🛠️ Tools & Technical Skills
* [cite_start]**Power BI Desktop:** Report authoring, UI/UX design, and interactive slicer implementation[cite: 62, 64].
* [cite_start]**DAX:** Custom measures for **Total Sales**, **Margin %**, and **RANKX** for competitive benchmarking[cite: 34, 65].
* [cite_start]**Python (pandas):** Pre-processing, data cleaning, and CSV export[cite: 23, 28, 63].
* [cite_start]**GitHub:** Version control and portfolio hosting[cite: 66].

---
