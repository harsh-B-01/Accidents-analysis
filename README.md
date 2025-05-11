🚗 UK Road Accident Analysis – Power BI Project

📊 Project Overview

This project presents an in-depth analysis of UK road accident data using **Power BI**, with the goal of identifying key trends, patterns, and insights to support **data-driven road safety improvements**. The dataset, sourced from the UK Department for Transport and hosted in a **PostgreSQL** database, includes detailed records of accidents, vehicle involvement, casualties, and environmental conditions.

---

🎯 Objectives

- Develop an interactive Power BI dashboard for visual exploration of UK road accident data.
- Identify trends based on accident severity, vehicle types, and casualty demographics.
- Analyze the impact of environmental factors such as weather, road surface, and lighting.
- Detect regional accident hotspots to inform safety measures and policy recommendations.

---

🛠️ Tools & Technologies

- **Power BI** – Dashboard design and data visualization  
- **PostgreSQL** – Data storage and querying  
- **Power Query** – Data transformation and cleaning  
- **DAX** – Custom calculations, KPIs, and measures  

---

📌 Key Features

- **Interactive Dashboard**: Users can filter data dynamically by region, time, vehicle type, weather, and more.
- **Casualty Analysis**: Detailed views by severity (fatal, serious, slight) and distribution over time.
- **Geospatial Visualization**: Map-based accident plotting using latitude and longitude data.
- **Trend Monitoring**: Year-over-year visual comparisons and heatmaps to track changes.
- **KPI Cards**: Real-time updating metrics for total casualties, regional contribution, and severity distribution.

---

🔍 Key Insights

- The **South Eastern region** reported the **highest casualty rate**, accounting for approximately **25% of all casualties** across the UK.
- **Urban areas** with high traffic density showed the highest concentration of accidents, especially during peak hours.

---

## 🧩 Challenges & Solutions

- **Mapping Regions Without Region Fields**:  
  Used latitude and longitude to derive approximate UK regions using custom logic.

- **Large Dataset Performance**:  
  Optimized data model and applied efficient DAX measures to ensure responsive dashboard performance.

---

## 📈 Impact

This project provides a robust, data-driven tool for **government agencies, safety analysts, and transportation authorities** to identify critical accident hotspots and prioritize preventive actions. It emphasizes the power of visual analytics in public safety and transportation planning.

---

## 📁 File Structure

- `UK_Road_Accident_Analysis.pbix` – Main Power BI file  
- `README.md` – Project documentation


