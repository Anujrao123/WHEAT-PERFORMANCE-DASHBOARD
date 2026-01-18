# WHEAT-PERFORMANCE-DASHBOARD
Power BI dashboard analyzing wheat production, yield, and performance trends to support agricultural data-driven decision making.
## 📌 Project Overview
This Wheat Performance Dashboard is developed using Power BI to analyze
wheat production data and identify performance trends across different
dimensions. The dashboard transforms raw agricultural data into clear
and actionable insights that help in understanding crop performance
and productivity.

## 🎯 Business Objectives
- Analyze wheat production and yield performance
- Identify trends over time
- Compare performance across regions or categories
- Support data-driven agricultural decisions

## 📈 Key KPIs
- Total Wheat Production
- Average Yield
- Area Cultivated
- Production Growth %
- Yield per Unit Area

## 📊 Dashboard Visuals
- KPI Cards – Production, Yield, Area
- Line Chart – Production Trend
- Bar Chart – Region-wise Wheat Production
- Donut Chart – Contribution by Category
- Table – Detailed Production Summary

## 🛠️ Tools & Skills Used
- Power BI
- DAX (Measures & Calculations)
- Data Cleaning
- Data Modeling
- Data Visualization

## 🧮 Sample DAX Measures
```DAX
Total Production = SUM(Wheat[Production])

Average Yield = AVERAGE(Wheat[Yield])

Yield per Area = DIVIDE([Total Production], SUM(Wheat[Area]), 0)

power-bi
agriculture-dashboard
wheat-analysis
crop-performance
data-analytics
data-visualization
powerbi-dashboard
dax
kpi-dashboard
portfolio-project
