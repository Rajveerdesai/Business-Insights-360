# Business-Insights-360
  An 8-page, 150+ visual Power BI dashboard consolidating Finance, Sales, Marketing, and Supply Chain analytics into a single, executive-facing Business Intelligence (BI) tool for AtliQ Hardware, a global consumer electronics hardware company.

📊 Business Insights 360 — AtliQ Hardware

An 8-page, 150+ visual Power BI dashboard consolidating Finance, Sales, Marketing, and Supply Chain analytics into a single, executive-facing Business Intelligence (BI) tool for AtliQ Hardware, a global consumer electronics hardware company.
🌍 Business Context

AtliQ Hardware operates across 23 countries and serves 90+ global customers, ranging from large retail chains (Amazon, BestBuy, Walmart) to regional distributors. As the business scaled, its Finance, Sales, Marketing, and Supply Chain functions each maintained separate, disconnected reporting — a common Enterprise Reporting challenge where fragmented data silos prevent leadership from getting a single source of truth for business performance.

❗ Problem Statement

Without a consolidated reporting layer, leadership had no unified way to:

🎯 Benchmark actual performance against sales targets across regions
💰 Track Profit & Loss (P&L) trends across fiscal years and quarters
🏆 Identify top-performing vs. underperforming customers, products, and markets
📦 Monitor Supply Chain forecast accuracy to reduce stockouts and excess inventory

This lack of centralized Business Intelligence slowed down strategic decision-making and made cross-functional performance comparisons difficult.

✅ Solution

I designed and built a unified, multi-page Power BI dashboard that functions as a single Executive Reporting layer across the organization — enabling leadership to drill down from a high-level summary into function-specific detail without switching between disconnected spreadsheets or reports.

🧭 Dashboard Architecture
Page	Business Function	What It Covers
🏠 Home	Navigation-	Landing page and cross-dashboard navigation
💰 Finance View	Finance & Accounting-	P&L Statement, Net Sales, Gross Margin, GM%, Year-over-Year (YoY) benchmarking
📈 Sales View-	Sales	Customer performance analysis, revenue contribution by account
📣 Marketing View	-Marketing	Performance Matrix, Unit Economics, product-level marketing effectiveness
📦 Supply Chain View-	Operations / Supply Chain	Forecast Accuracy, Net Error, Absolute Error — demand planning diagnostics
🔍 P&L Check-	Finance	Fiscal-year-wise P&L validation and reconciliation
📉 Sales Trend-	Sales	Quarterly and monthly sales trend analysis
👔 Executive View-	Leadership / C-Suite	Top 5 Customers, Top 5 Products, Revenue by Division and Channel
📌 Key Business Metrics Delivered
Metric	Value	Business Insight
📈 Net Sales Growth	$87.5M (2019) → $598.9M (2021)	304.5% YoY growth trend identified
💵 Gross Margin	$218.2M	36.4% overall margin rate across fiscal years
🌐 Customer Base Analyzed	90+ customers	Spanning 23 countries globally
⚠️ Market Performance vs. Target	-$54.9M (-9.2%)	Shortfall flagged against sales targets, highlighting underperforming markets
🛠️ Tools, Skills & Business Concepts Applied

Technical Skills:

📊 Power BI Desktop — end-to-end report design and multi-page dashboard architecture
🗃️ SQL — querying and extracting customer, sales, and transaction data from relational tables using Joins, Subqueries, and Views prior to modelling in Power BI
🧮 DAX (Data Analysis Expressions) — calculated measures for Net Sales, Gross Margin %, and Target Variance
🔗 Data Modelling — relational schema linking customer, sales, and time-dimension tables to enable accurate cross-page filtering (star-schema style modelling)
🧹 Power Query (M) — ETL processes: data cleaning, transformation, and fiscal calendar table creation
📗 Advanced Excel — supporting P&L and gross margin analysis prior to Power BI integration

Business & Domain Concepts:

💰 Profit & Loss (P&L) Statement Analysis
📉 Gross Margin % and Cost of Goods Sold (COGS) Analysis
📅 Year-over-Year (YoY) Performance Benchmarking
🎯 Sales Target vs. Actual (Variance Analysis)
🧩 Customer & Product Performance Segmentation
📦 Demand Forecasting and Forecast Accuracy (Supply Chain Analytics)
👔 Executive/C-Suite Reporting and KPI Design
💡 What I Learned

This project pushed me beyond just building visuals — it required thinking like a Business Analyst, not just a report builder:

🔗 Data Modelling matters more than dashboard design. Structuring the relationships between tables correctly meant a single filter selection (e.g., Fiscal Year or Region) updated metrics consistently across all 8 pages — a foundational Business Intelligence principle.
👀 Executives don't read reports, they scan them. Designing the Executive Summary taught me to prioritize the 3-4 numbers that matter most (Top Customers, Top Products, Revenue by Channel) rather than overwhelming the page with every available metric.
🎯 Variance analysis drives action. Simply reporting "$598.9M in Net Sales" is descriptive. Reporting "-9.2% shortfall against target" is prescriptive — it tells leadership exactly where to focus.
🤝 Cross-functional thinking is essential. Consolidating Finance, Sales, Marketing, and Supply Chain into one tool required understanding how these functions influence each other (e.g., forecast inaccuracy in Supply Chain directly impacts Gross Margin in Finance).
