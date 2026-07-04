# 🍔 Buffalo Burger: Sales & Operations Performance Analysis

## 📊 Overview
This repository contains a comprehensive, data-driven performance analysis for **Buffalo Burger**, a leading gourmet burger chain. The project processes raw transactional data, customer feedback, and branch operations to deliver actionable insights aimed at optimizing menu engineering, improving customer retention, and streamlining order fulfillment workflows.

---

## 🛠️ Tech Stack & Architecture
* **Data Warehousing & Querying:** SQL (Structured extraction of sales logs, ticket items, and branch metrics)
* **Data Processing & ETL:** Python (Pandas, NumPy for data cleaning, cohort analysis, and anomaly detection)
* **Business Intelligence:** Power BI (Interactive reporting canvas, relational data modeling, and DAX)
* **Design Engineering:** Custom JSON layouts for high-contrast, corporate dark/light theme execution

---

## 📂 Repository Structure
```text
├── Data/
│   ├── Raw/                             # Anonymized sales logs, itemized orders, and customer feedback
│   └── Processed/                       # Aggregated tables and analytical cohorts
├── SQL_Queries/
│   ├── sales_aggregations.sql           # Store-by-store performance summaries
│   └── customer_lifetime_value.sql      # RFM segmentation parameters
├── Dashboards/
│   └── Buffalo_Burger_Performance.pbix # Core Power BI development file
└── README.md                            # Project documentation
```
## 🚀 Key Analytical Insights & Features

### 1. Menu Engineering & Product Affinity (Basket Analysis)
* **High-Margin Performers:** Segmented the entire menu by item profitability to isolate the highest revenue-generating gourmet burgers (e.g., Old School, Double Jab).
* **Cross-Selling Strategies:** Implemented Market Basket Analysis to discover deep item affinity, mapping frequent add-on behaviors (appetizers, sauces, and dynamic combos) to actively boost Average Order Value (AOV).

### 2. Delivery & Branch Efficiency Analysis
* **Fulfillment Latency:** Tracked the complete preparing-to-delivery lifecycle across all branches to pinpoint operational bottlenecks and mitigate peak-hour delivery delays.
* **Geographical Demand Mapping:** Dissected store-level telemetry to evaluate regional demand patterns, local item preferences, and supply chain constraints.

### 3. Customer Retention & Sentiment Profiling
* **RFM Segmentation:** Grouped customer cohorts based on Recency, Frequency, and Monetary parameters to easily differentiate loyal brand advocates from churning customer segments.
* **Sentiment Integration:** Maintained text-parsing logic on qualitative customer feedback to align visual delivery ratings directly alongside specific branch operation logs.

### 4. Financial & Dynamic Margin Tracking
* **Dynamic Time Intelligence:** Integrated advanced DAX parameters to compare Year-over-Year (YoY) performance and Month-to-Date (MTD) revenue pacing against dynamic corporate targets.
* **Payment Method Distribution:** Evaluated checkout metrics (Cash, Visa, Digital Wallets) to track operational cash flows, conversion rates, and payment processing fees.

---

## 📥 Getting Started

### 📋 Prerequisites
* **Power BI Desktop:** The latest version is highly recommended for full compatibility with visual layouts.
* **SQL Environment:** A local or cloud SQL instance to host and execute the foundational analytical queries.

