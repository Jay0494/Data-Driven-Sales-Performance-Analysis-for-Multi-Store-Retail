# 📊 Sales Performance Analysis – Multi-Store Retail Business (Indonesia)

## 📌 Project Overview

This project analyzes sales performance for a fast-growing multi-store retail business operating across major cities in Indonesia. The goal was to transform raw transactional data into a **decision-ready analytics framework** that supports operational optimization, performance monitoring, and scalable growth.

The analysis focuses on **store performance, product contribution, sales channels, demand dynamics, and growth trends** using SQL and Power BI.

---

## 🏢 Business Context

The business operates **five physical retail stores** and sells over **25 products** through retail, online, and wholesale channels.
Although sales data was available through the POS system, leadership lacked:

* A consolidated performance view
* Clear visibility into revenue drivers
* Evidence-based insights for scaling decisions

As a result, decision-making was largely **reactive and intuition-driven**.

---

## ❗ Business Problem

Key questions management could not confidently answer:

* Which stores contribute most to total revenue?
* How evenly is revenue distributed across locations and products?
* Which customer channels drive sales?
* Is revenue growth driven by demand (volume) or pricing?
* How has performance evolved since launch?

This project addressed those gaps by building a **structured sales analytics framework**. 

---

## 🎯 Project Objectives

* Create a single source of truth for sales performance
* Enable store-level and product-level comparison
* Identify demand patterns and early growth signals
* Support data-driven operational and strategic decisions
* Establish a scalable foundation for future reporting

---

## 🔍 Scope of Analysis

Included:

* Transactional sales data since business launch (2025)
* 5 store locations across Indonesia
* Daily and monthly sales activity
* Revenue and quantity sold metrics

Excluded:

* Cost data
* Profitability analysis
* External market or macroeconomic data

---

## 🧰 Tools & Technologies

**SQL**

* Data extraction and validation
* Duplicate checks and data quality controls
* Aggregation by store, product, channel, and time

**Power BI**

* Star-schema data modeling
* KPI development and interactive dashboards
* Time-series trend analysis

---

## 🧪 Analytical Approach

### 1. Data Preparation (SQL)

* Validated completeness and consistency
* Identified and removed duplicate records
* Standardized date formats and key fields
* Generated analysis-ready aggregated datasets

### 2. Data Modeling (Power BI)

* Built a clean fact-dimension model
* Created relationships between sales, stores, products, and calendar tables

### 3. Performance Analysis

* Store-level revenue contribution
* Product-level performance
* Sales channel distribution
* Time-based trends and growth analysis

---

## 📊 Key Business Questions Answered

* Which stores generate the highest revenue share?
* How diversified is revenue across products and channels?
* Is growth driven by demand volume or pricing?
* How has sales evolved month-over-month?
* Where should management focus optimization efforts?

---

## 📈 Key Insights

### 🏬 Store Performance

Revenue contribution is relatively balanced across all locations:

| Store           | Revenue Share |
| --------------- | ------------- |
| Surabaya Center | 22.08%        |
| Median Square   | 20.14%        |
| Plaza Jakarta   | 20.01%        |
| Mall Bandung    | 19.06%        |
| Denpasar Point  | 18.72%        |

**Insight:**
Low dependency on any single store indicates stable operations. Performance gaps are incremental, making them suitable for targeted optimization rather than restructuring.

---

### 📆 Sales Timing

* Weekday revenue: **59.25%**
* Weekend revenue: **40.75%**

**Insight:**
Higher weekday activity suggests stronger demand during standard operating days. This has implications for staffing, inventory planning, and promotion timing.

---

### 🛒 Sales Channel Performance

* Retail: **39.98%**
* Online: **30.74%**
* Wholesale: **29.28%**

**Insight:**
A balanced channel mix reduces concentration risk and provides flexibility to scale channels independently.

---

### 📦 Product Performance

Top revenue-contributing products:

* P15, P18, P12, P20, P13

**Insight:**
Revenue is partially concentrated among a subset of SKUs, indicating the need for deeper SKU-level dependency and risk analysis.

---

### 📐 Demand Dynamics

* Correlation between revenue and quantity sold: **0.90**

**Insight:**
Revenue growth is primarily **volume-driven**, not price-driven. Inventory availability and demand fulfillment are key performance levers.

---

### 📈 Growth Trends

Significant month-over-month growth spikes:

* **May:** +94.27%
* **December:** +101.55%

**Insight:**
These spikes suggest possible seasonality, promotional impact, or demand acceleration and warrant further investigation.

---

## 📌 Key Performance Indicators (KPIs)

| KPI                             | Value       |
| ------------------------------- | ----------- |
| Net Revenue                     | 822.2M      |
| Total Discounts                 | 100.78M     |
| Total Transactions              | 750         |
| Sales Volume                    | 4,000 units |
| Average Transaction Value (ATV) | 1.10M       |
| Number of Stores                | 5           |

---

## 🧠 Business Interpretation

* High net revenue combined with moderate transaction volume suggests **strong basket sizes**
* Discount levels are material relative to revenue, highlighting potential **margin optimization opportunities**
* Channel-level basket size and customer segmentation analysis would provide further clarity

---

## 📌 Strategic Recommendations

**Jakarta & Surabaya**

* Prioritize high-demand SKUs
* Maintain stronger inventory buffers
* Pilot operational improvements before wider rollout

**Bandung**

* Use as a controlled testing environment for new products and bundles

**Denpasar**

* Align offerings with tourism-driven demand
* Strengthen digital discoverability for non-local customers

---

## 🚀 Business Impact

This project converted raw transactional data into a **scalable sales analytics framework** that enables:

* Continuous performance monitoring
* Clear identification of demand drivers
* Data-backed optimization decisions
* A repeatable foundation for future reporting and forecasting

---

## 🔍 Next Questions for Further Analysis

* Were growth spikes driven by promotions, external events, or organic growth?
* Did performance normalize after peak months?
* Were growth spikes consistent across stores or localized?
* Did peak periods generate repeat customers or one-off buyers?

---

## 📊 Dashboard

**[Sales Performance Dashboard]**(https://app.powerbi.com/view?r=eyJrIjoiMzVkNTVhNjgtOWNhMi00N2FkLThjODAtNTI1NTkwM2FmMTA2IiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9)


