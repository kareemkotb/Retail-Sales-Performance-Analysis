#🛒 Retail Sales Performance Analysis

End-to-end exploratory analysis of a US superstore dataset — uncovering revenue drivers, margin leaks, and actionable recommendations for the sales leadership team.


📌 Project Overview
This project analyzes four years of retail transaction data from a US superstore to answer key business questions around revenue, profitability, regional performance, customer segmentation, and the financial impact of discounting.
The analysis was conducted entirely in Python and follows a structured pipeline: data ingestion → cleaning → EDA → visualization → executive summary.

📊 Dataset
DetailInfoSourceSuperstore Dataset — KaggleFileSample - Superstore.csvEncodingISO-8859-1CoverageUS retail orders with order/ship dates, product categories, regions, segments, sales, profit, and discount

🔍 Key Business Questions

Which product category generates the most sales and the most profit?
Which sub-category is the most profitable — and which is losing money?
Which region performs best by both sales and profit?
Which customer segment brings the highest revenue?
How does discounting correlate with profitability?


💡 Key Findings
FindingDetail🏆 Top revenue categoryTechnology💰 Top profit categoryTechnology📈 Best region (sales)West📈 Best region (profit)West👤 Highest-revenue segmentConsumer✅ Most profitable sub-categoryCopiers❌ Biggest loss-making sub-categoryTables⚠️ Discount impactProfitability declines as discount levels increase

Bottom line: Revenue and profit are not always aligned at a granular level. Category-level growth can hide sub-category losses. Discount guardrails — especially on Tables, Bookcases, and Supplies — are needed to protect margins.


🗂️ Project Structure
retail-sales-analysis/
│
├── Retail_Sales_Performance_Analysis.ipynb   # Main analysis notebook
├── Sample - Superstore.csv                   # Source dataset (download from Kaggle)
└── README.md

🛠️ Tech Stack
ToolPurposePython 3.xCore languagepandasData loading, cleaning, aggregationnumpyNumerical operationsmatplotlibCustom charts and trend linesseabornStatistical visualizations (regression scatter)

📈 Visualizations Produced

Bar chart — Order distribution by Category
Bar chart — Order distribution by Sub-Category
Line chart — Monthly Sales Trend (time series)
Grouped bar chart — Sales by Region × Customer Segment
Scatter + regression — Discount vs. Profit relationship
