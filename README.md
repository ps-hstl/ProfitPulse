💡 ProfitPulse
A data-powered dashboard to decode vendor performance, optimize inventory dynamics, and boost supply chain profitability using Python, SQL, and Power BI.

📊 Project Overview
ProfitPulse delivers strategic insights into vendor and brand performance for retail and wholesale businesses. By integrating purchase, sales, and freight data, it uncovers hidden patterns and empowers decision-makers to boost margins, minimize inventory risks, and maximize procurement efficiency.

🧠 Problem Statement
Retail and wholesale operations frequently face:

Excess unsold inventory

Inefficient vendor relationships

Pricing blind spots

ProfitPulse tackles these by:

Pinpointing underperforming brands

Ranking vendors based on revenue and profit impact

Evaluating the benefits of bulk purchasing

Assessing stock turnover and financial leakage

Recommending pricing strategies based on profit margin analysis

📂 Project Structure
graphql
Copy
Edit
├── Exploratory Data Analysis.ipynb       # Initial exploration and data cleaning
├── ProfitPulse_Final_Analysis.ipynb      # Main analysis, visualizations, insights
├── get_vendor_summary.py                 # Data transformation & summary builder
├── ingestion_db.py                       # Raw CSV ingestion to SQLite DB
├── vendor_sales_summary.csv              # Output metrics for each vendor
├── profitpulse_dashboard.pbix            # Power BI interactive dashboard
├── ProfitPulse_Report.pdf                # Final insights and strategic recommendations
├── logs/                                 # Script monitoring logs
└── data/                                 # Raw input CSVs
📈 Key Features
End-to-End Data Pipeline: Transforms CSVs into a query-ready database

Smart Merging & Cleaning: SQL-based joining of freight, sales, and purchase data

Custom KPIs Engineered: Gross Profit, Stock Turnover, Sales-to-Purchase Ratio

Exploratory Insights: Negative margins, unsold goods, high-margin vendors

Interactive Power BI Dashboard: Visual drill-down of brand/vendor performance

PDF Report: Key takeaways, trend charts, and executive recommendations

📊 KPIs & Metrics Computed
Gross Profit & Profit Margin

Total Sales & Purchase Volume

Stock Turnover Ratio

Sales-to-Purchase Ratio

Vendor Contribution to Revenue

Bulk Buying Efficiency

Vendor Segmentation: High vs. Low Performers

🔍 Insights & Findings
📌 Top 10 Vendors contribute 65%+ of purchases
📌 Bulk purchases reduce unit cost by 72%
📌 $2.71M in unsold stock linked to underperforming vendors
📌 Vendors with low volume but high margins can be strategic assets
📌 Action plan: Re-evaluate pricing, optimize inventory, and diversify vendors
