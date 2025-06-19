# Vendor_Performance_Analysis
An interactive, data-driven dashboard solution for procurement and supply chain professionals—designed to evaluate vendor performance across delivery, cost, and profitability metrics using real transactional data.

📝Purpose
  The Vendor360 Dashboard helps stakeholders monitor vendor efficiency across multiple KPIs such as purchase vs. sales volume, profit margins, stock turnover, and delivery patterns. This tool supports strategic decision-making, vendor negotiations, and inventory optimization.

🛠 Tech Stack
  The dashboard and backend were built using the following technologies:
  
  💽 MS SQL Server – Data storage, cleansing, and transformation using complex joins and CTEs
  
  🐍 Python (pandas, numpy, SQLAlchemy) – Automated ETL and intermediate KPI calculations
  
  📓 Jupyter Notebook – Exploratory data analysis (EDA), visual diagnostics, and hypothesis testing
  
  📊 Power BI Desktop – Visualization layer with dynamic filters, KPIs, and deep-dive dashboards
  
  🔄 Power Query & DAX – Used for modeling, measure creation, conditional formatting, and interactivity
  
  🗂 Data Source
  Source: Simulated vendor data exported from internal ERP systems

Tables:

purchases: product name, vendor, purchase price, quantity

sales: sales volume, price, and profit metrics

vendor_invoice: delivery details and freight costs

purchase_prices: benchmark pricing over time

Data Volume: 50+ vendors, 1000s of transactions, structured across 4+ relational tables

⭐ Features / Highlights
• Business Problem
  Procurement teams often deal with large vendor networks and lack a clear overview of vendor performance. Questions such as:
  
  Are high-margin vendors contributing meaningfully to total profit?
  
  Which vendors hold slow-moving inventory?
  
  Is bulk buying actually cost-effective?
  
  ... are hard to resolve using fragmented reports.

• Goal of the Dashboard
To provide a single-pane, interactive view of all vendors’ performance in terms of cost, sales, profit, inventory movement, and efficiency.
This empowers:
Procurement heads to negotiate smarter
Analysts to find underperformers
Executives to make inventory and pricing decisions backed by data

• Walkthrough of Key Visuals
📌 Top KPIs Panel
  Total Purchase Value
  
  Total Sales Value
  
  Average Profit Margin
  
  Stock Turnover Rate
  
  Vendors with Slow-Moving Inventory

🧾 Vendor-wise Comparison (Bar + Scatter)
Bar chart: Total Purchase vs. Total Sales by Vendor

Scatter Plot: Profit Margin vs. Stock Turnover (identify outliers)

💡 High Margin but Low Sales Vendors
Table + Cards highlighting vendors who earn more per unit but contribute little to total revenue

📉 Inventory Movement
Stacked bar: Quantity Purchased vs. Quantity Sold

Identify excess stock or dead stock vendors

📦 Unit Cost Optimization
Line chart showing price drop in bulk purchase

Supports bulk discount negotiation

📈 Profitability Trends
Time-based trendline showing profit progression

Useful for spotting consistent vs. seasonal vendors

• Business Impact & Insights
  📌 Procurement Optimization:
  Identify high-margin but underutilized vendors to explore scaling or marketing their SKUs.
  
  📉 Cost Reduction:
  Evidence shows bulk purchases can reduce unit prices by up to 70%—supports pricing strategy.
  
  ⏳ Inventory Efficiency:
  Highlight slow-moving stock (~$2.7M frozen capital) to trigger clearance strategies.
  
  🧮 Data-Driven Vendor Ranking:
  Quantitative metrics enable unbiased vendor selection and reward strategies.
  
🧾 Screenshots for Demo
  ![Vendor Performance Dashboard](https://github.com/user-attachments/assets/49463e11-7920-4dcb-b565-ef06d9f1293a)

  
