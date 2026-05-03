# 📊 Technology Sales Analysis (Excel)

## 📌 Project Overview

This project presents an in-depth sales performance analysis of the **Technology category** from the Superstore Sales Dataset using Microsoft Excel.

The dataset contains transaction-level sales data including:

- Order & Ship Dates
- Customer Segment & Region
- Product Sub-Category
- Sales, Profit & Quantity
- Shipping Mode & Duration
- City & State

The primary objective of this analysis was to evaluate:

- Year-over-year sales and profit growth
- Sub-category profitability gaps
- Regional and city-level revenue distribution
- Shipping behaviour and operational trends

---

## 📂 Dataset Summary

| Metric | Value |
|---|---|
| Total Sales | $836,154 |
| Total Profit | $145,455 |
| Total Orders | 1,847 |
| Profit Margin | 17% |
| Date Range | 2014 – 2017 |
| Sub-Categories | 4 (Phones, Accessories, Machines, Copiers) |
| Top City | New York City ($109,316) |
| Peak Month | November ($131,135) |

---

## 🧹 Data Cleaning

The dataset was transformed in **Power Query (Excel)** where the following checks and transformations were carried out:

- Filtered dataset to **Technology category only**
- Removed duplicate records
- Fixed date column data types (Order Date, Ship Date)
- Added **Profit Margin %** column → `Profit / Sales`
- Added **Shipping Duration** column → `Ship Date - Order Date` (whole number of days)
- Added **Year** column → `Date.Year([Order Date])`
- Added **Month** column → `Date.MonthName([Order Date])`
- All columns confirmed to be in the correct data type

---

## ❓ Business Problem

The business lacks a clear, real-time view of how technology product sales are performing across sub-categories, regions and time periods.

Specifically, the business could not answer:

1. Are we growing year over year — and by how much?
2. Which sub-categories are genuinely profitable and which are losing money?
3. Which regions and cities are driving the most revenue?
4. Are our shipping operations keeping up with order growth?

---

## 🔎 Insight Questions Explored

1. What is the year-over-year change in Sales, Profit, Orders and Quantity?
2. Which sub-category generates the highest sales vs the highest profit?
3. Which month records the highest sales volume?
4. Which cities are the top revenue contributors?
5. What shipping mode do most customers use — and how long do deliveries take?
6. How is sales revenue distributed across U.S. states?

---

## 📊 Dashboard Preview

![Technology Sales Analysis](https://github.com/simplysmarty/Technology-Sales-Analysis/blob/main/SALES%20DASHBOARD.png?raw=true)
### Dashboard Components

| Visual | Description |
|---|---|
| **5 KPI Cards** | Total Sales, Total Profit, Total Quantity, Profit Margin, Total Orders — each with YoY indicator |
| **Sales Trend Line Chart** | Monthly sales performance across the year with peak month callout |
| **Profit vs Sales Bar Chart** | Side-by-side comparison of Sales and Profit across all 4 sub-categories |
| **Shipping Duration Lollipop Chart** | Distribution of delivery days with % of orders at each duration |
| **Ship Mode Donut Chart** | Breakdown of Standard, Second, First Class and Same Day shipping |
| **U.S. Filled Map** | Sales distribution by state across the United States |
| **Top Cities Bar Chart** | Revenue contribution of the top 5 performing cities |
| **Slicers** | Year (2014–2017), Customer Segment (Consumer, Corporate, Home Office) |

---

## 📈 Key Findings

### 1️⃣ Strong Year-Over-Year Growth (2016 → 2017)

| Metric | YoY Change |
|---|---|
| Sales | ▲ 20.0% |
| Profit | ▲ 27.4% |
| Orders | ▲ 35.9% |
| Quantity | ▲ 39.2% |
| Profit Margin | ▲ 6.2% |

The business is growing across every key metric. Profit is growing faster than sales — a sign that margins are improving.

### 2️⃣ Copiers Are the Hidden Gem

Copiers generate **$55,618 in profit at a 37% margin** — the highest of all four sub-categories — yet they account for the lowest sales volume. This product is significantly underinvested relative to its profit potential.

### 3️⃣ Machines Are a Strategic Problem

Machines generated **$189,241 in sales** but only **$3,374 in profit** — a margin of just 1.8%. Despite strong revenue numbers, this sub-category is consuming resources and returning almost nothing. Discounting or pricing is likely the root cause.

### 4️⃣ November is the Peak Sales Month

November recorded **$131,135 in sales** — the highest single month across the entire dataset. Q4 consistently outperforms all other quarters.

### 5️⃣ New York City Leads All Cities

New York City generated **$109,316 in revenue** — more than double Seattle ($42.5K) and significantly ahead of every other city. The East and West regions drive the majority of revenue.

### 6️⃣ Standard Class Dominates Shipping

**59% of all orders** use Standard Class shipping. Most orders (28%) are delivered in **4 days** — a reasonable fulfilment window given the shipping mode distribution.

---

## ⚠️ Limitations

- Dataset covers U.S. market only — no international comparison possible
- No customer-level data — repeat purchase behaviour cannot be analysed
- Discount data available in the full Superstore dataset but not explored in this analysis
- Machines' profitability issue requires cost and discount data to fully diagnose

---

## 🚀 Recommendations

### 1️⃣ Invest More in Copiers
At a 37% profit margin, Copiers are the most profitable sub-category and are being underutilised. Increase sales focus, marketing spend and stock availability around this product immediately.

### 2️⃣ Audit the Machines Pricing and Discount Strategy
A 1.8% profit margin on $189K in revenue is not sustainable. A full review of discount levels, cost structure and pricing for Machines is required before further investment in this sub-category.

### 3️⃣ Capitalise on Q4 Momentum
November is consistently the strongest month. A deliberate Q4 strategy — targeted promotions, increased stock, sales rep incentives — could amplify what is already the business's best trading period.

### 4️⃣ Double Down on New York City and Top Cities
New York City generates more revenue than the next two cities combined. Dedicated account management, regional promotions and increased sales effort in top-performing cities would yield disproportionate returns.

### 5️⃣ Monitor Shipping Capacity as Orders Grow
Orders grew 35.9% year over year. With 59% of customers on Standard Class, any logistics strain will be felt broadly. Reviewing shipping partnerships and capacity now — before the next growth cycle — is a proactive step worth taking.

---

## 🛠 Tools Used

**Microsoft Excel**
- Power Query — Data Cleaning & Transformation
- Pivot Tables — Aggregation & Summarisation
- Calculated Columns — Profit Margin %, Shipping Duration, Year, Month
- Conditional Formatting — YoY Arrow Indicators (Green ▲ / Red ▼)
- Dynamic Slicers — Year, Customer Segment
- Charts — Line, Clustered Bar, Lollipop, Donut, Filled Map

---



## 📌 Conclusion

The Technology Sales Dashboard transforms 1,847 rows of raw transactional data into a clear, interactive view of business performance. The analysis reveals a business that is growing strongly — but one where the growth is uneven. Copiers are underutilised, Machines are underperforming, and New York City is carrying a disproportionate share of revenue.

The data does not make decisions but it removes every excuse for making bad ones.

---

*Analysed by: Segun Fasanya | Data Analytics Portfolio Project | 2026*
