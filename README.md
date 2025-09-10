**Vendor Performance Data Analysis**
This project analyzes vendor performance in the retail and wholesale sector using Python-based data analysis and an interactive Power BI dashboard. The goal is to uncover inefficiencies in pricing, supplier dependency, inventory management, and profitability, and to provide data-driven recommendations that improve business outcomes.

✅ Problems Solved

Pricing inefficiencies → Found 198 brands with high margins but low sales.
Vendor dependency → Top 10 vendors contribute 65.7% of purchases, creating risk.
Inventory issues → $2.71M worth of unsold stock identified.
Profitability gaps → High- vs low-performing vendors shown to follow different models (validated with hypothesis testing).
Cost savings → Bulk purchasing reduces unit costs by 72%.

💡 Use Cases
Retailers & Wholesalers → Optimize vendor contracts and pricing strategies.
Procurement Teams → Leverage bulk purchasing for better deals.
Financial Analysts → Detect capital tied up in unsold stock.
Business Leaders → Make data-backed decisions on supplier diversification.
Data Science Portfolios → Demonstrates applied analytics and BI integration.

📊 Dashboard (Power BI)
An interactive dashboard provides an executive-friendly view of vendor performance.
Metrics Displayed:
Total Sales: $441.41M
Total Purchases: $307.34M
Gross Profit: $134.07M
Profit Margin: 38.7%
Unsold Capital: $2.71M
Visuals Include: Vendor contribution %, top brands/vendors, low-performing suppliers, and profit margin analysis.

📷 Screenshot of dashboard:
<img width="2880" height="1799" alt="Power BI Desktop 05_09_2025 23_02_47" src="https://github.com/user-attachments/assets/96b9e5b0-a7c2-44d8-9a2c-eb2eed65ae7c" />

🔍 Python Analysis
Data Cleaning → Removed invalid and zero-sale records.
Exploratory Data Analysis (EDA) → Outlier detection, margin analysis, sales distribution.
Correlation Analysis → Explored relationships between pricing, profit, and turnover.
Hypothesis Testing → Confirmed profitability differences between vendor groups.
Visualizations → Heatmaps, bar charts, scatter plots, and trend analysis.

Business Impact
By applying these insights, businesses can:
Recalibrate pricing and promotions for underperforming brands.
Diversify supplier base to reduce risks.
Encourage bulk purchasing for cost efficiency.
Optimize inventory to improve cash flow.
Apply tailored strategies for vendors based on their performance models.

🛠️ Tools & Technologies
Python → Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels
Jupyter Notebook → Exploratory data analysis
Power BI → Interactive dashboard
Visualization → Clear, business-focused insights

📂 Repository Structure
Vendor-Performance-Analysis/
│
├── data/                     # Raw and cleaned datasets
├── notebooks/                # Jupyter notebook with full analysis
│   └── vendor_analysis.ipynb
├── reports/                  # Final reports
│   └── Vendor Performance Report.pdf
├── visuals/                  # Graphs & dashboard screenshots
│   └── vendor_dashboard.png
├── dashboard/                # Power BI file
│   └── vendor_performance.pbix
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation

📑 Getting Started
Clone Repository
git clone https://github.com/your-username/vendor-performance-analysis.git
cd vendor-performance-analysis

Install Requirements
pip install -r requirements.txt

Run Notebook
jupyter notebook notebooks/vendor_analysis.ipynb

Explore Dashboard
Open dashboard/vendor_performance.pbix in Power BI Desktop.

📜 License: This project is licensed under the MIT License – free to use and adapt.
