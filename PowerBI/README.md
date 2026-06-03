# Sales Performance Dashboard — Power BI

An interactive Power BI report analyzing sales performance across regions, product categories, and time periods. Built as part of an analytics portfolio to demonstrate DAX, data modeling, and dashboard design skills.

---

## Report Pages

### 1. Overview
The main dashboard providing a high-level snapshot of business performance.

| Visual | Description |
|--------|-------------|
| KPI Card — Total Sales | Overall revenue at a glance |
| Card — Target | Sales target for context |
| Clustered Column Chart — Total Sales by Continent | Revenue breakdown across continents |
| Clustered Bar Chart — Margin % by Product Category | Profitability comparison by category |
| Line Chart — Sales Performance | Trend analysis over time |
| Slicers — Continent, Year | Interactive filters for cross-report analysis |

### 2. Sales Regions
Geographic breakdown of performance.

| Visual | Description |
|--------|-------------|
| Pie Chart — Total Sales by Country | Revenue share by country |

### 3. Product Sales Details
Granular time-series view of product-level sales.

| Metric | Description |
|--------|-------------|
| Total Sales | Absolute revenue |
| YTD Sales | Year-to-date cumulative sales |
| PY Total Sales | Prior year comparison |
| Total Sales YoY% | Year-over-year growth percentage |

### 4. DAX Demos
A showcase of custom DAX measures used throughout the report.

| Measure | Description |
|---------|-------------|
| Total Sales | Sum of all sales revenue |
| Total Margin % | Overall profitability percentage |
| Count of Sales Orders | Total number of orders |
| Count of Sales Order Line Items | Total line items across all orders |
| Count of Sales Order Line Items GT 50 | Line items with value greater than 50 |
| PCT Sales Orders Line Items All Time | Percentage of line items relative to all-time total |

---

## Key DAX Concepts Demonstrated

- **Time Intelligence** — YTD, Prior Year comparisons, YoY growth
- **Aggregations** — Sales totals, margin calculations
- **Filtering** — Conditional counts with filter context
- **Ratio Calculations** — Percentage metrics across different contexts

---

## Tools & Technologies

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Data Modeling** — relationships across sales, product, and date tables

---

## How to Use

1. Open `Sales.pbix` in Power BI Desktop
2. Use the **Continent** and **Year** slicers on the Overview page to filter the entire report
3. Navigate between pages using the tabs at the bottom
4. Visit the **DAX Demos** page to inspect the underlying measures

---

## Author

**Zarraf Afnan**
CS Student — Ontario Tech University (Graduating December 2026)
[GitHub](https://github.com/zarrafafnan) · [LinkedIn](https://www.linkedin.com/in/zarrafafnan)
