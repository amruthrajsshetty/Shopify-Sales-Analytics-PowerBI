# Shopify Sales & Customer Retention Intelligence Dashboard

An executive Power BI analytics project analyzing 7,431 Shopify transactions ($4.60M in gross sales) to uncover patterns in revenue generation, product performance, and customer cohort retention.

---

## Key Performance Indicators (KPIs)
* **Total Gross Revenue:** $4,598,960.87
* **Total Orders:** 7,431
* **Average Order Value (AOV):** $618.89
* **Unique Customers:** 4,431
* **Repeat Purchase Rate:** 46.02% (2,039 repeat buyers)
* **Average Repurchase Latency:** 2.06 days (49.54 hours)

---

## Core Business Findings
* **Footwear Concentration:** Running Shoes ($1.62M) and Tennis Shoes ($972K) account for over 56% of gross store revenue.
* **Customer Retention:** 46.02% of buyers placed 2 or more orders, with repeat purchases occurring within 48 to 72 hours of initial checkout.
* **Pareto Revenue Distribution:** The top 20% of customers generate 37.84% ($1.74M) of total gross revenue.

---

## Tech Stack & Architecture
* **Tool:** Power BI Desktop
* **ETL:** Power Query (type casting, text normalization, date/time extraction)
* **Data Modeling:** Star Schema with a dedicated calendar dimension (`Dim_Date`)
* **Measures:** DAX formulas for dynamic revenue, order volume, AOV, and customer cohort repeat rates
