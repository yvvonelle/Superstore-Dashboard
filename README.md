# Superstore Sales Performance: Executive Power BI Report

## Project Overview
This project transforms  Superstore transactional data into a high-impact interactive dashboard. The objective was to move beyond basic reporting and uncover the "story" within the data: identifying which products drive genuine profit, how regional trends shift, and the specific threshold where discounting begins to destroy value.

This analysis provides a data-driven look at retail health, offering critical insights for inventory optimization and regional pricing strategies.

---

## Data Architecture & ETL
To ensure high-performance filtering and data integrity, the project followed a structured technical pipeline:
* **Data Cleaning (Python):** Used **pandas** to remove duplicate records and verify the integrity of all financial columns.
* **Feature Engineering:** Standardized all temporal data into datetime objects and derived a custom **Ship Duration** column to track fulfillment efficiency.
* **DAX Modeling:** Developed a dedicated **Measures Table** to house complex logic, including YoY Sales Growth, Profit Margin %, and dynamic Product Rankings.
* **Refined Schema:** Organized the dataset to support seamless cross-highlighting across four distinct analytical zones.

---

## Dashboard Architecture
The report is designed as a single-page executive summary divided into four logical pillars:

### KPI Performance Strip
**Goal:** Establish an immediate baseline of organizational health.
* **Visuals:** KPI Cards for Total Sales, Profit, and Average Discount.
* **Key Insight:** Integrated **Year-over-Year (YoY) Sales Growth** with conditional arrows to show growth trends at a glance.

### Discounting & Profit Correlation
**Goal:** Quantify the financial friction caused by aggressive pricing.
* **Visuals:** **Scatter Chart** with a trend line to map the relationship between Discount % and Net Profit.
* **Key Insight:** Identifies the "danger zone" where discounts of **30% or higher** lead to consistent losses.

### Geographic & Customer Value
**Goal:** Optimize regional resource allocation and identify true high-value customers.
* **Visuals:** **Filled Map** (Color saturation = Sales) and a Top Customer Table.
* **Key Insight:** Highlights the gap between high-revenue customers and high-profit customers to guide loyalty strategies.

---

---

## How to Access
1. **Clone** this repository and download the `Superstore_Dashboard.pbix` file.
2. **Open** in Power BI Desktop.
3. **Update** the data source path to your local copy of `superstore_clean.csv` if prompted.
4. **Interact** with the top **Slicer Panel** (Year, Region, Segment, Category) to explore the data layers.
