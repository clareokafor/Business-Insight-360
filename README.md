# Business Insight 360

## Overview

Business Insight 360 is a Power BI project built for **AtliQ Hardware** to provide a single view of business performance across:

- Finance
- Sales
- Marketing
- Supply Chain
- Executive Management

The project uses more than **1.8 million records** from **MySQL and Excel**.

I used **Power Query** for data preparation, **DAX** for calculations, and **DAX Studio** to improve model performance.

The goal was to create one interactive reporting solution that helps users understand not just sales, but also profitability, forecasting, customer performance, product performance and inventory risk.

---

## Data Sources

The project combines data from:

- **MySQL**
- **Excel**

The datasets cover areas such as:

- Sales
- Customers
- Products
- Markets
- Regions
- Gross margin
- Net profit
- Forecast accuracy
- Inventory risk
- Market share
- Revenue contribution
- Profit and loss

---

## Data Preparation and Modelling

The data preparation process included:

- Connecting Power BI to MySQL and Excel sources
- Cleaning and transforming data using **Power Query**
- Standardising fields across datasets
- Creating relationships between fact and dimension tables
- Building the data model in Power BI
- Creating business measures using **DAX**
- Using **DAX Studio** to review and improve performance
- Adding filters, slicers and report navigation

The final report can be filtered by:

- Region
- Market
- Customer
- Segment
- Category
- Product
- Year
- Quarter
- YTD
- YTG
- Last Year
- Target

---

# Dashboard Views

## 1. Finance View

The Finance View focuses on overall financial performance and Profit & Loss reporting.

### Key KPIs

- **Net Sales:** $823.85M
- **Gross Margin:** 36.5%
- **Net Profit:** -6.6%

### Analysis Included

- Profit and Loss Statement
- Net Sales Performance Over Time
- Gross Margin
- Net Profit
- Regional P&L performance
- Segment performance
- Comparison against benchmarks and previous periods

The report makes it easier to understand how revenue, cost and profitability are connected.

![Finance View](finance-view.png)

---

## 2. Sales View

The Sales View focuses on customer, product and market performance.

### Key Metrics

- **Net Sales:** $823.8M
- **Gross Margin:** $300.6M
- **Gross Margin %:** 36.5%

### Analysis Included

- Customer Performance
- Product Performance
- Regional Performance
- Gross Margin analysis
- Performance Matrix
- Unit Economics

The report allows users to compare customers and products based on sales and margin rather than looking at revenue alone.

![Sales View](sales-view.png)

---

## 3. Marketing View

The Marketing View looks at profitability across products, customers and markets.

### Key KPIs

- **Net Sales:** $823.8M
- **Gross Margin:** $300.6M
- **Net Profit:** -$54.7M
- **Net Profit %:** -6.6%

### Analysis Included

- Product Performance
- Region / Market / Customer Performance
- Performance Matrix
- Net Profit analysis
- Unit Economics

One of the main insights from this view is that strong sales do not always translate into strong profitability.

Some products and markets generated high revenue but still recorded negative net profit margins.

![Marketing View](marketing-view.png)

---

## 4. Supply Chain View

The Supply Chain View focuses on forecast accuracy, inventory risk and demand planning.

### Key KPIs

- **Forecast Accuracy:** 80.2%
- **Net Error:** -751.7K
- **Absolute Error:** 9780.7K

### Analysis Included

- Forecast Accuracy
- Net Error
- Absolute Error
- Customer Risk
- Product Risk
- Forecast Accuracy Trend
- Net Error Trend

The report also classifies supply chain risk as:

- **OOS** — Out of Stock
- **EI** — Excess Inventory

This helps highlight where forecasting errors may be affecting product availability or creating excess stock.

![Supply Chain View](supply-chain-view.png)

---

## 5. Executive View

The Executive View brings together the main KPIs from across the business.

### Key KPIs

- **Net Sales:** $823.85M
- **Gross Margin:** 36.5%
- **Net Profit:** -6.6%
- **Forecast Accuracy:** 80.2%

### Analysis Included

- Revenue by Division
- Revenue by Channel
- Yearly Performance Trends
- Market Share
- Customer Performance
- Product Performance
- Sub-Zone Performance

The report also compares performance across revenue channels such as:

- Retailer
- Direct
- Distributor

The Retailer channel contributed the largest share of revenue.

![Executive View](executive-view.png)

---

## Key Findings

The analysis showed that:

- Net Sales were above **$823M**
- Gross Margin remained positive at around **36.5%**
- Net Profit was negative at around **-6.6%**
- Forecast Accuracy was around **80.2%**
- Some customers and products showed **Out-of-Stock risk**
- Other areas showed **Excess Inventory risk**
- Revenue performance varied across markets, products and regions
- Some high-revenue products still recorded negative net profit margins
- Retailer was the strongest revenue channel
- Strong sales performance did not always translate into strong profitability

---

## Why This Analysis Matters

Looking at sales alone does not give a complete picture of business performance.

This project brings together finance, sales, marketing and supply chain data so users can understand how different parts of the business affect each other.

For example:

- Strong sales may still lead to weak profitability
- Poor forecast accuracy may cause stock-outs or excess inventory
- High-performing customers may not always have the strongest margins
- A product can generate strong revenue while still recording a negative net profit
- Market share can change even when sales are growing

Bringing these views together makes it easier to identify where the business is performing well and where closer attention is needed.

---

## Tools Used

- **Power BI**
- **Power Query**
- **DAX**
- **DAX Studio**
- **MySQL**
- **Excel**
- **Data Modelling**
- **Data Cleaning**
- **Data Transformation**
- **Data Visualisation**
- **Business Intelligence**

---

## Live Dashboard

[**View the interactive Business Insight 360 Power BI dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZGRhNjYwYTUtZWE3Zi00MzkyLWJhMmItZDE0NzY3NjFkYjJiIiwidCI6ImYyMDIxN2JmLWEwYzYtNDZlNi1hMTdmLTY3YzkwNTY0NDgwZiJ9)

---

## Key Takeaway

Business Insight 360 shows how different areas of a business can be analysed together rather than in isolation.

The project demonstrates that strong sales do not automatically mean strong business performance. Looking at profitability, forecast accuracy, market share and inventory risk alongside revenue gives a much clearer view of how the business is actually performing.

---

## License

This project is licensed under the **MIT License**.

[LICENSE](LICENSE.txt)
