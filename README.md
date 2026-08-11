# 🚖 UBER Trip Demand & Operational Performance Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811.svg?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Calculated_Measures-blue.svg)](https://learn.microsoft.com/en-us/dax/)
[![Data Analytics](https://img.shields.io/badge/Data_Analytics-Demand_Forecasting-green.svg)](https://github.com/JaiswalKritika)

An interactive, multi-view **Power BI Business Intelligence Dashboard** analyzing over **100,000+ Uber trip records**. Designed to optimize driver allocation, identify peak booking hours, analyze spatial pickup/dropoff patterns, and provide actionable business recommendations for operational efficiency.

---

## 📊 Business Objectives & Analytical Scope

1. **Demand & Revenue Optimization**: Track total bookings, revenue value, and trip distances dynamically across time windows.
2. **Temporal Pattern Discovery**: Identify peak vs off-peak hours and weekday vs weekend demand fluctuations to optimize surge pricing strategies.
3. **Geospatial & Vehicle Analysis**: Pinpoint top pickup/dropoff hubs and vehicle type preferences across urban zones.

---

## 🌟 Dashboard Architecture & Views

### 1. 🚖 Demand & Location Analysis Dashboard
- **Dynamic KPI Selector**: Switch seamlessly between *Total Bookings*, *Total Booking Value*, and *Total Trip Distance* using a dynamic DAX measure filter.
- **Top Pickup & Dropoff Hubs**: Pinpoints high-density trip origins and destinations using relationship activation.
- **Vehicle Type Matrix**: Breakdown of bookings, revenue, and average trip length across vehicle tiers (UberGO, Premier, XL, Auto) with conditional formatting.

### 2. ⏰ Time & Hourly Trend Analysis Dashboard
- **10-Minute Pickup Area Chart**: High-resolution demand tracking across 10-minute intervals throughout 24-hour cycles.
- **Day-of-Week Trendline**: Booking volume analysis comparing weekday commuting vs weekend nightlife peaks.
- **Hour x Day Heatmap Grid**: 24x7 matrix highlighting exact peak hours to guide driver dispatch schedules.

### 3. 📋 Granular Trip Details Grid Tab
- **Drill-Through Functionality**: Enables users to right-click on any visual (e.g. specific hour or location) and drill through into full raw records.
- **Bookmark Controllers**: One-click toggles for *"View Full Data"*, *"Data Dictionary Panel"*, and *"Reset All Filters"*.

---

## 🛠️ Tech Stack & Methods

- **Analytics Tool**: Microsoft Power BI Desktop
- **Data Modeling & Calculations**: Data Analysis Expressions (DAX), Power Query (M Language)
- **Visuals Used**: Matrix Grids, Area Charts, Heatmaps, Custom Slicers, Bookmark Buttons
- **Data Engine**: Star Schema dimensional modeling

---

## 💡 Key Business Insights

- **Peak Commute Window**: 8:00 AM – 10:00 AM and 5:30 PM – 8:00 PM represent 48% of total daily trip demand.
- **High-Density Corridors**: Top 5 pickup locations generate over 35% of total revenue.
- **Vehicle Preference**: Executive vehicle tiers experience a 22% higher average trip distance compared to standard economy rides.

---

## 👤 Author

**Kritika Jaiswal**  
- LinkedIn: [Kritika Jaiswal](https://www.linkedin.com/in/kritika-jaiswal205)  
- GitHub: [@JaiswalKritika](https://github.com/JaiswalKritika)
