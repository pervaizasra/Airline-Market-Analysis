📌 Project Summary

This project explores trends in U.S. domestic air travel using 245,000+ records of route-level data.
It combines Python-based data analysis, statistical hypothesis testing, and an interactive Power BI dashboard to support real-world business decisions in the aviation industry.

🎯 Objectives

Analyze air travel demand and average fare trends over time

Identify peak travel quarters and seasonal effects

Compare market share and fare strategies of major and low-cost carriers

Generate route-level KPIs such as Fare per Mile, Passenger Volume

Conduct statistical hypothesis tests to validate insights

Visualize results via an interactive Power BI dashboard

🛠️ Tools & Technologies

Tool	Purpose
Python (Pandas, Seaborn, Scipy)	Data cleaning, EDA, statistical testing
Power BI	Dashboard creation & interactive reporting
Jupyter Notebook	Step-by-step data analysis
GitHub	Project version control and showcase

📂 Repository Structure
Airline-Market-Analysis/
│
├── data/                     # Cleaned & derived datasets (CSV)
│   ├── market_cleaned.csv
│   ├── kpi_quarterly.csv
│   ├── kpi_route.csv
│   ├── kpi_carrier_share.csv
│   └── peak_quarter.csv
│
├── images/                   # Python visuals for hypothesis tests
│   ├── fare_comparison.png
│   ├── q1_q3_volume.png
│   ├── distance_fare_correlation.png
│   └── wn_market_share.png
│
├── dashboard_screenshots/    # Power BI pages
│   ├── executive_summary.png
│   ├── route_insights.png
│   ├── seasonality.png
│   └── carrier_performance.png
│
├── notebook.ipynb            # Full Python analysis
├── statistical_analysis.md   # Markdown summary of all 4 hypothesis tests
└── README.md                 # This file

📊 Key Findings

Hypothesis	Result

LCC fares < Large Carrier fares	✅ Significant (p < 0.001)

Q3 > Q1 passenger volume	✅ Significant (p = 0.0051)

Route Distance ↘ Fare per Mile	✅ Negative correlation (r = -0.598)

Post-2019 growth in WN share	❌ Not significant (p = 0.2883)

📎 See full statistical analysis

📈 Power BI Dashboard Overview

Each page of the dashboard answers a key business question.

Page 1: Executive Summary

Total Passengers & Avg Fare (KPI Cards)

Yearly Trends (Line Charts)

Carrier Market Share (Pie)

Filters: Year, Quarter

Page 2: Route Insights

Top 10 Routes (Bar)

Route KPIs: Distance, Fare, Fare/Mile

Map (Geocoded Routes)

Page 3: Seasonality & Quarters

Quarterly Passenger Trends

Peak Travel Quarter KPIs

Page 4: Fare Competitiveness

Scatter: fare_lg vs fare_low

Histogram: Fare Distribution

Avg Fare Gap Card

Page 5: Carrier Performance

Passengers by Carrier (Bar)

Fare Trend by Carrier (Line)

Fare/Passenger KPIs

📸 View dashboard screenshots

💼 Business Recommendations

🛫 High-Demand Routes: Increase frequency on top routes to match demand.

💸 Fare Gaps: Monitor pricing where large carriers are uncompetitive.

📉 Underperformers: Evaluate low-volume routes or weak carrier sectors.

📆 Seasonality: Prepare for Q3 with staff and aircraft planning.

📊 Market Share: Track rising LCCs and stabilize legacy carriers’ positions.

📁 Resources
📄 Statistical Analysis Report

📊 Notebook (EDA + Testing)

📁 Cleaned Datasets

🙌 Author
Asra Pervaiz
🔹 Aviation + Business Intelligence + Data Analytics
🔹 LinkedIn | Portfolio | Email

⭐ Like this project?
Leave a ⭐ on the repo or connect with me on LinkedIn! This project is part of my data portfolio built to showcase real-world business intelligence and analytics skills.
