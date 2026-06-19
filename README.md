# 📊Retail Sales Analysis Dashboard

An interactive Power BI dashboard built on the Global Superstore dataset, analyzing sales, profit, and customer performance across regions, markets, and product categories — with built-in time-intelligence forecasting.

## 🎯Overview

This project transforms raw retail order data into a 5-page interactive dashboard designed to help business stakeholders quickly identify sales trends, profitability gaps, top customers, and seasonal patterns.

## 🛠️Tools Used

- **Power BI Desktop** — data modeling, DAX measures, visualization
- **DAX** — calculated measures (YTD, YoY comparisons, forecasting)
- **Power Query** — data cleaning and transformation

## 📁Dashboard Pages

**1️⃣ Executive Summary Dashboard**
- Profit by category, monthly sales & profit trends
- Sales by market and country (map visual)
- Sales breakdown by sub-category and market

**2️⃣ Product Performance**
- Total profit by segment, sales by sub-category
- Top products by sales (ranked)
- Sales vs. profit scatter analysis by sub-category

**3️⃣ Customer Analysis**
- Customer segmentation and YTD sales
- Top customers by average sales and by profit
- Monthly customer trends

**4️⃣ Time Intelligence**
- Sales & profit forecasting (predictive trend lines)
- YTD vs. YTD Last Year comparison
- Decomposition tree for root-cause analysis
- Regional sales treemap; sales & profit ribbon chart by market

**5️⃣ Tooltip Page**
- Custom hover tooltip showing regional sales breakdown

## 🔍 Key Insights
- **APAC** was the highest-performing market by sales (~$3.59M), followed by EU (~$2.94M) and US (~$2.30M)
- **Technology** had the strongest profit margin (~14%) among categories, while **Furniture** lagged at just ~7% despite generating $4.1M in sales
- **Tables** stood out as a high-sales, negative-margin sub-category ($757K in sales but a **-8% margin**, i.e. a net loss) — a clear pricing/discount risk area
- Year-over-year sales grew consistently from 2011 to 2014 (from ~$2.26M to ~$4.30M), and the forecast model projects this **upward trend continuing**

## 🚀 How to Use
1. Download `Global_Superstore.pbix`
2. Open in Power BI Desktop (free download from Microsoft)
3. Use slicers on each page to filter by region, segment, category, or date

## 📂 Dataset
[Global Superstore](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset) — a widely-used retail dataset containing order-level sales, profit, and customer data across global markets.

⭐ *If you found this project useful, feel free to star the repo!*
