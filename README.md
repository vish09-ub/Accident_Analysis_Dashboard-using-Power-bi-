# 🚦 Accident Analysis with Power BI

This project presents a visual analytics report on road traffic accidents using real-world datasets. It explores the severity of accidents, driver behavior, vehicle involvement, environmental conditions, and regional patterns to extract meaningful insights that can help improve road safety measures.

## 📌 Project Overview

Road traffic accidents are a major global concern. By analyzing datasets containing accident records, vehicle details, and casualty information, this project uses Power BI to present interactive dashboards for better understanding and decision-making.

### 🔍 Objectives

- Classify accidents based on severity and identify key risk factors.
- Analyze driver demographics and vehicle types involved in accidents.
- Study how weather and road surface conditions affect accident severity.
- Explore time-based and regional trends in accident occurrence.
- Provide actionable recommendations for improving road safety.

## 🗂️ Datasets Used

**Accidents Dataset**: 60,000+ records with fields like date, time, location, severity, road surface, and weather.
- **Vehicles Dataset**: Vehicle type, driver age, fuel type, journey purpose, and more.
- **Casualties Dataset**: Age, gender, injury severity, and casualty type.

## 🧹 Data Cleaning & Integration

- Removed missing/inconsistent values from critical fields.
- Mapped driver age into bands (e.g., 17–25, 26–35).
- Standardized categorical values.
- Merged datasets using `Accident_Index` as a primary key.
- Derived fields like "Time of Day" and "Peak Hour Flag".

## 📊 Dashboard Features

Built using **Power BI**, the dashboard includes:

- **Overview Page**: Total accidents, gender split, severity distribution.
- **Severity & Conditions**: Impact of weather and road conditions.
- **Time & Location Trends**: Daily/monthly trends and high-incident zones.
- Visual elements: Pie charts, bar charts, line graphs, heatmaps, and maps.

## 💡 Key Insights

- Young male drivers (26–35) are most frequently involved.
- Most accidents occur during clear weather, suggesting behavioral causes.
- Two-wheelers show higher risk in wet conditions.
- Pedestrians and passengers are most vulnerable.
- High accident spikes during June and December (holiday season).

## 🛠️ Tools Used

- **Power BI**: Dashboard creation and interactive visualizations.
- **Excel**: Initial data inspection and formatting.
- **Python (Optional)**: For data preprocessing (Pandas, NumPy).

## ✅ Recommendations

- Awareness programs for high-risk age groups.
- Better pedestrian infrastructure near schools/hospitals.
- Road maintenance for slippery zones.
- Promote helmet and ABS usage in motorcycles.
- Smarter emergency response systems.


