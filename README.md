# 🛒 Retail Sales Performance Analysis

End-to-end exploratory analysis of a US superstore dataset — uncovering revenue drivers, margin leaks, and actionable recommendations for the sales leadership team.


# 📌 Project Overview
This project analyzes four years of retail transaction data from a US superstore to answer key business questions around revenue, profitability, regional performance, customer segmentation, and the financial impact of discounting.
The analysis was conducted entirely in Python and follows a structured pipeline: data ingestion → cleaning → EDA → visualization → executive summary.

# 🔍 Key Business Questions

Which product category generates the most sales and the most profit?
Which sub-category is the most profitable — and which is losing money?
Which region performs best by both sales and profit?
Which customer segment brings the highest revenue?
How does discounting correlate with profitability?


# 💡 Key Findings
FindingDetail
🏆 Top revenue category: Technology
💰 Top profit category: Technology
📈 Best region (sales)West
📈 Best region (profit)West
👤 Highest-revenue segmentConsumer
✅ Most profitable sub-categoryCopiers
❌ Biggest loss-making sub-categoryTables
⚠️ Discount impact Profitability declines as discount levels increase

Bottom line: Revenue and profit are not always aligned at a granular level. Category-level growth can hide sub-category losses. Discount guardrails — especially on Tables, Bookcases, and Supplies — are needed to protect margins.


# 🗂️ Project Structure
retail-sales-analysis/
│
├── Retail_Sales_Performance_Analysis.ipynb   # Main analysis notebook
├── Sample - Superstore.csv                   # Source dataset (download from Kaggle)
└── README.md


# 📈 Visualizations Produced

Bar chart — Order distribution by Category
Bar chart — Order distribution by Sub-Category
Line chart — Monthly Sales Trend (time series)
Grouped bar chart — Sales by Region × Customer Segment
Scatter + regression — Discount vs. Profit relationship

# 📋 Executive Summary

Revenue is primarily driven by Technology, with Consumer as the strongest customer segment and the West region contributing the highest sales overall.
Profitability is being eroded by specific sub-categories — Tables represent the largest loss-maker, with additional margin pressure from Bookcases and Supplies.
Higher discount levels are strongly associated with weaker profit outcomes, visible in the regression trend where profitability declines as discounts increase.
The same areas driving revenue are not always equally profitable at a granular level — category-level growth can mask sub-category losses.

# 🎯 Recommended Action
Implement discount guardrails (especially for Tables and other loss-making sub-categories) while prioritizing high-performing combinations (Technology × Consumer × West) to grow revenue without eroding margin.
