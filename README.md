# 📱 Mobile Sales Analysis Dashboard | Power BI
![ image alt ](https://github.com/25PriyankaRawat1234/Mobile_Sales_Analysis_Project/blob/8bd87e2feead36ed6b28813504f3b929919b9432/Project.png)
## Table of Contents

* [Brief One-Line Summary](#brief-one-line-summary)
* [Overview](#overview)
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Tools and Technologies](#tools-and-technologies)
* [Methods](#methods)
* [Insights](#insights)
* [Dashboard Output](#dashboard-output)
* [Dashboard Preview](#dashboard-preview)
* [Business Questions and Insights](#business-questions-and-insights)
* [How to Run This Project](#how-to-run-this-project)
* [Results and Conclusion](#results-and-conclusion)
* [Future Work](#future-work)
* [Author and Contact](#author-and-contact)
* [Project Highlights](#project-highlights)

---

## Brief One-Line Summary

Interactive Power BI dashboard built to analyse 430 mobile phone records, brand performance, estimated revenue, sales quantity, pricing, discounts, product specifications and customer ratings.

---

## Overview

This project analyses mobile phone sales data using Microsoft Power BI to identify brand performance, popular mobile models, pricing patterns and customer rating trends.

The dashboard transforms raw product and sales data into an interactive analytical report that helps users compare mobile brands, evaluate product performance and explore differences in pricing, discounts and customer feedback.

The project focuses on converting raw data into meaningful KPIs, visual comparisons and business-oriented insights.

---

## Problem Statement

Mobile phone retailers and businesses need to understand which brands and models perform well, how products differ in price, and how customer ratings vary across products.

The objective of this project is to explore the available data and answer practical business questions through interactive visualisations.

### Key Objectives

* Analyse estimated revenue and sales quantity across mobile phone brands.
* Identify the top-performing mobile phone models.
* Compare brand-level pricing and discount patterns.
* Examine customer ratings and review volumes.
* Explore product specifications such as RAM, ROM, battery capacity and display size.
* Build an interactive dashboard to support product and pricing comparisons.
* Present data-driven findings while recognising the limitations of the dataset.

---

## Dataset

The project uses a mobile phone dataset provided in Microsoft Excel format.

### Dataset Highlights

* **430 records**
* **16 columns**
* **5 mobile phone brands**
* Product and model information
* Sales prices and discount percentages
* Sales quantities
* Customer ratings and review counts
* Mobile phone technical specifications

### Key Columns

* Brand
* Model
* Base Color
* Processor
* RAM
* ROM
* Display Size
* Screen Size
* Camera Specifications
* Battery Capacity
* Sales Price
* Discount Percentage
* Sales Quantity
* Customer Ratings
* Number of Ratings

### Dataset Considerations

The dataset does not contain a date field or product cost information.

Therefore, the analysis focuses on the supplied sales, pricing, product and customer-rating fields rather than time-series forecasting or profit calculations.

The revenue metric is estimated using sales price multiplied by sales quantity. It should not be interpreted as verified company-wide revenue.

---

## Tools and Technologies

| Tool                | Purpose                                    |
| ------------------- | ------------------------------------------ |
| Microsoft Power BI  | Interactive dashboard development          |
| Power Query         | Data cleaning and transformation           |
| DAX                 | Calculated columns and analytical measures |
| Microsoft Excel     | Source dataset and data inspection         |
| Power BI Visuals    | KPI cards, charts, tables and comparisons  |
| Slicers and Filters | Interactive data exploration               |

---

## Methods

### Data Preparation

* Imported the Excel dataset into Power BI.
* Reviewed column names and data types.
* Checked data quality and missing values.
* Reviewed duplicate records.
* Examined categorical values for inconsistencies.
* Prepared the dataset for analysis and visualisation.
* Reviewed unusual values in the processor category before interpreting them.

### Data Analysis

* Brand-wise Estimated Revenue Analysis
* Brand-wise Sales Quantity Analysis
* Top-Selling Mobile Model Analysis
* Average Selling Price Comparison
* Discount Percentage Analysis
* Customer Rating Analysis
* Review Volume Analysis
* RAM and ROM Comparison
* Battery Capacity and Display Specification Analysis
* Brand and Model Performance Comparison

### Dashboard Development

The Power BI report is organised into five analytical pages:

1. Overview
2. Sales Performance
3. Customer Preferences & Pricing
4. Ratings & Brand Comparison
5. Insights Drawn

The dashboard combines KPI cards, comparative charts, tables and interactive filtering to help users explore different aspects of mobile phone performance.

---

## Insights

The analysis of the supplied dataset highlights the following findings.

### Key Findings

**1. Realme leads estimated revenue**

Realme generates approximately ₹5.14 crore in estimated revenue, making it the leading brand among the five brands analysed.

**2. Realme records the highest sales quantity**

Realme has an aggregated sales quantity of 4,231 units in the dataset.

**3. Xiaomi has a strong-performing model**

The Redmi Note 7 Pro records an aggregated sales quantity of 713 units, the highest among the individual models analysed.

**4. Apple has a higher average selling price**

Apple has an average listed selling price of approximately ₹57,748 and estimated revenue of approximately ₹4.47 crore.

**5. Discount patterns differ across brands**

Poco records the highest average discount percentage among the five brands, at approximately 16%, while Realme's average discount is approximately 8%.

**6. Customer ratings provide another comparison dimension**

Apple has the highest average brand rating in the dataset, at approximately 4.56 out of 5.

These findings describe the available dataset. They do not establish that discounts cause higher sales or that ratings directly determine revenue.

---

## Dashboard Output

The report contains five pages designed to explore different analytical perspectives.

### Page 1: Overview

Provides a high-level summary of mobile sales performance through KPIs and brand-level comparisons.

### Page 2: Sales Performance

Examines sales quantity, estimated revenue and leading mobile phone models.

### Page 3: Customer Preferences & Pricing

Explores product prices, discounts and technical specifications.

### Page 4: Ratings & Brand Comparison

Compares average customer ratings and review volumes across brands and models.

### Page 5: Insights Drawn

Summarises key findings and potential business implications derived from the analysis.

---

## Dashboard Preview

### 1. Overview

![ image alt ](https://github.com/25PriyankaRawat1234/Mobile_Sales_Analysis_Project/blob/fb1c96522ef3e9a2f41ce972c7a7e5df5c75aa33/Key_Objectives.png)
### 2. Sales Performance

![ image alt ](https://github.com/25PriyankaRawat1234/Mobile_Sales_Analysis_Project/blob/d997920e81a6c40535c04f9b1df025f9f7b1fdfe/Mobile_Sales_Data_Overview1.png)

### 3. Customer Preferences & Pricing

![ image alt ](https://github.com/25PriyankaRawat1234/Mobile_Sales_Analysis_Project/blob/72da6a77449c7d0ba704e9cbbf08aa1e810187a5/Mobile_Sales_Data_Overview2.png)

### 4. Ratings & Brand Comparison

![ image alt ](https://github.com/25PriyankaRawat1234/Mobile_Sales_Analysis_Project/blob/a42620b33c6452fe3482cad74241db73eb6627ff/Mobile_Sales_Data_Overview3.png)

### 5. Insights Drawn

![Key Insights Dashboard](screenshots/key-insights.png)

*Note: Add your actual Power BI screenshots to the `screenshots` folder using these filenames so that the images display correctly on GitHub.*

---

## Business Questions and Insights

The dashboard is designed to answer practical questions about mobile phone sales and product performance.

### Questions Addressed

* Which mobile phone brand generates the highest estimated revenue?
* Which brand records the highest sales quantity?
* What are the top 10 mobile phone models by sales quantity?
* Which models contribute the most to estimated revenue?
* How does average selling price differ across brands?
* Which brand has the highest average discount percentage?
* Which brand has the highest average customer rating?
* How do ratings and review volumes vary across models?
* How do mobile phone specifications differ between brands?
* Which models combine relatively high prices with strong sales quantities?
* How can brand-level comparisons help identify potential product and pricing opportunities?

### Interactive Analysis

Users can explore the dashboard by applying the available slicers and filters.

The exact filter options depend on the visuals and slicers configured in the Power BI report.

---

## How to Run This Project

1. Clone or download this GitHub repository.

2. Open the `dashboard` folder and download the Power BI report:

   `Mobile_Sales_Analysis.pbix`

3. Open the file using Microsoft Power BI Desktop.

4. If Power BI cannot locate the source dataset, update the data source path to the downloaded Excel file in the `data` folder.

5. Refresh the dataset if required.

6. Navigate through the five report pages.

7. Use the available slicers, filters, charts and tables to explore brand performance, sales quantity, pricing and customer ratings.

**Requirements:** Microsoft Power BI Desktop and access to the source Excel dataset.

---

## Results and Conclusion

This project demonstrates how Power BI can transform raw mobile phone data into an interactive analytical dashboard.

The analysis identifies Realme as the leading brand by estimated revenue and sales quantity in the supplied dataset. It also highlights Xiaomi's strong model-level sales quantity, Apple's higher average selling price and the differences in discount and customer-rating patterns across brands.

The dashboard brings together product specifications, sales quantities, estimated revenue, pricing and customer feedback to provide a broader view of mobile phone performance.

The project follows the analytical workflow:

**Raw Data → Data Preparation → DAX Measures → Visualisation → Business Insights**

It demonstrates practical skills in data preparation, analytical calculations, dashboard design and communicating data-driven findings.

---

## Future Work

Potential improvements for future versions include:

* Adding a reliable date field for sales trend analysis.
* Integrating additional datasets for market-level comparisons.
* Performing deeper analysis of product specifications and sales quantity.
* Comparing actual selling prices with original prices, where available.
* Investigating the relationship between discounts and sales quantity.
* Exploring customer ratings alongside review volumes.
* Adding drill-through pages for individual brands and models.
* Improving data validation and category standardisation.
* Integrating SQL-based data sources.
* Developing additional DAX measures for advanced comparative analysis.

These improvements would depend on the availability of suitable data.

---

## Author and Contact

**Priyanka Rawat**

Aspiring Data Analyst | Power BI | Excel | SQL | Python

**LinkedIn:**
[linkedin.com/in/priyanka-rawat-9121073a4](https://www.linkedin.com/in/priyanka-rawat-9121073a4/)

---

## ⭐ Project Highlights

**430 Records** | **16 Columns** | **5 Mobile Phone Brands**

**₹19.60 Crore Estimated Revenue** | **12,591 Sales Quantity**

Built with **Microsoft Power BI, Power Query, DAX and Microsoft Excel**.

*Revenue is estimated as Sales Price × Sales Quantity. All findings are limited to the supplied dataset.*
# Mobile_Sales_Analysis_Project
