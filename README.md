# 🛒 Retail Sales Analytics Dashboard (Power BI)
An interactive Power BI dashboard that analyses retail sales performance across
regions, cities, store formats, categories, and brands in Central India.

## 📌 Business Questions Answered
- Is business concentrated in a few cities or evenly distributed?
- Which states drive revenue and higher basket values?
- Do higher-tier cities (T2 vs T3) perform better?
- Which cities represent our strongest markets?
- What are the top 10 categories, brands, and SKUs in a city?
- Which brands balance sales, price, and volume?

## 📊 Dashboard Pages
| Page | Description |
|------|-------------|
| Regional Overview | KPIs, state and city performance, tier and store-format split, monthly trend |
| City Shopping Behaviour | Category ranking, brand comparison, top SKUs, month-over-month trend |

## 🔑 Key KPIs
- Sales (CY) and YoY growth
- Transactions
- Average Transaction Value (ATV)
- Quantity sold
- Customers shopped
- Spend Per Customer (SPC)

## 💡 Key Insights
- Total sales of ₹50.18M, up 20.3% vs last year.
- Madhya Pradesh contributes ~84% of sales; Chhattisgarh ~16%.
- T2 cities contribute ~69% of sales; T3 ~31%.
- Supermarket is the largest format (~45%), followed by Express and Fresh.
- Customer count grew 54.7% while spend per customer fell 22.2%.

## 🛠️ Tools Used
- Power BI Desktop
- DAX (measures for YoY growth, ATV, SPC, contribution %)
- Power Query (data cleaning)

## 📁 Project Structure
```
dashboard/   → Power BI file (.pbix)
data/        → raw and cleaned datasets
reports/     → PDF export of the dashboard

## ▶️ How to Use
1. Download or clone this repository.
2. Open `dashboard/retail_sales_dashboard.pbix` in Power BI Desktop.
3. Use the slicers (Year, Region, City, Category) to explore the data.

## 📝 Notes
- Regional Overview shows 2026 (Jan–May); City Shopping Behaviour shows 2025.

## 👤 Author
Nishant Pal
