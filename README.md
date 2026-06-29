# 🛒 Walmart Sales Analysis — Power BI Dashboard

An end-to-end business intelligence project analyzing Walmart's weekly store sales across 45 stores. Built with Power BI, the report uncovers sales trends, holiday impacts, store-level performance, and the influence of external economic factors.

---

## 📊 Dataset Overview

| Field | Description |
|---|---|
| `Store` | Store identifier (1–45) |
| `Date` | Week start date |
| `Weekly_Sales` | Total sales for that store/week |
| `Holiday_Flag` | 1 = Holiday week, 0 = Non-holiday |
| `Temperature` | Average temperature (°F) |
| `Fuel_Price` | Regional fuel price ($/gallon) |
| `CPI` | Consumer Price Index |
| `Unemployment` | Regional unemployment rate |

**6,435 records** spanning multiple years across 45 Walmart stores.

---

## 📁 Project Structure

```
walmart-sales-powerbi/
│
├── Walmart.csv                          # Raw dataset
├── WALMART_SALES.pbix                   # Power BI report file
├── Walmart_PowerBI_Business_Questions.pdf  # Business questions & requirements
└── README.md
```

---

## 📑 Report Pages

The Power BI report is structured across 6 pages:

| Page | Description |
|---|---|
| **1 — Executive Dashboard** | KPIs: total revenue, average weekly sales, store count, top/bottom performers |
| **2 — Sales Trends** | Monthly & quarterly trends, YoY growth, highest/lowest months |
| **3 — Store Performance** | Store rankings, revenue contribution %, growth consistency, sales volatility |
| **4 — Holiday Analysis** | Holiday vs. non-holiday sales comparison, impact by holiday period |
| **5 — External Factors** | Correlation of sales with temperature, fuel price, CPI, and unemployment |
| **6 — Forecasting & Insights** | Projected future sales, expected holiday impact, store-level forecasts |

---

## 🔍 Key Business Questions Answered

### Executive Summary
- Total sales revenue and average weekly sales
- Number of stores in the dataset
- Highest and lowest performing stores

### Sales Performance
- Top 10 and Bottom 10 stores by total sales
- Monthly and quarterly sales trends
- Year-over-year growth analysis

### Holiday Impact
- Holiday weeks vs. non-holiday weeks comparison
- Average sales by holiday vs. non-holiday periods
- Which holiday period drives the highest sales

### Store Performance
- Revenue contribution percentage per store
- Stores with consistent growth vs. high fluctuation
- Overall store rankings

### External Factors
- Temperature vs. sales relationship
- Fuel price and CPI correlation with sales
- Unemployment impact on store performance

### Forecasting
- Projected upcoming weekly/monthly sales
- Future top-performing stores
- Expected holiday influence on future sales

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Data modeling, DAX measures, interactive visuals
- **Microsoft Excel / CSV** — Source data
- **DAX** — Custom KPIs, time intelligence, forecasting measures

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `WALMART_SALES.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `Walmart.csv` on your local machine
4. Refresh the data and explore all 6 report pages

> **Requirements:** Power BI Desktop (free) — [Download here](https://powerbi.microsoft.com/desktop/)

---

## 📌 Key Insights (Preview)

- Holiday weeks show a measurable uplift in average weekly sales compared to non-holiday periods
- A small subset of stores consistently drives a disproportionate share of total revenue
- External factors such as CPI and unemployment show notable correlations with store-level sales patterns
- Strong seasonal patterns exist, with Q4 typically recording peak revenues

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project uses publicly available Walmart sales data for educational and analytical purposes.

---

*Built with ❤️ using Power BI*
