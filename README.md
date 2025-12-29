# 📊 Seoul Bike Sharing Demand Analysis (Tableau)

## 📌 Project Overview
This project analyzes bike-sharing demand in Seoul using hourly rental data combined with weather and seasonal information. The objective is to understand **when**, **why**, and **under what conditions** bike demand changes in order to support better operational planning and resource allocation.

---

## 🎯 Project Goal
Analyze bike rental demand patterns across time, seasons, and weather conditions to identify peak usage periods and key factors influencing demand.

---

## 🏢 Business Problem
Bike-sharing demand fluctuates significantly based on time of day, season, holidays, and weather conditions. Without understanding these patterns, operators risk bike shortages during peak hours and underutilization during low-demand periods. This analysis helps support efficient bike allocation and operational decision-making.

---

## 🧩 Dataset
- **Source:** Seoul Bike Sharing Demand Dataset (CSV)
- **Granularity:** Hourly rental data
- **Key Fields:**
  - Date & Hour
  - Rented Bike Count
  - Temperature
  - Weather Conditions
  - Season
  - Holiday Indicator

The dataset was well-structured and connected directly to Tableau without heavy preprocessing.

---

## 📈 Key Metric (KPI)
- **Total Rented Bike Count**  
  Represents overall bike-sharing demand and serves as the primary performance indicator.

---

## 🔍 Key Dimensions
- Hour of Day  
- Date  
- Season  
- Holiday vs Non-Holiday  
- Weather & Temperature  

These dimensions enable time-based and condition-based demand analysis.

---

## 📊 Dashboards & Visualizations

### 🔹 Demand Forecasting
![Demand Forecasting](Images/Demand%20Forecasting.png)

**Description:**  
Shows hourly demand trends to identify peak and off-peak usage periods.

---

### 🔹 Demand by Day
![Demand by Day](Images/Demand%20by%20Day.png)

**Description:**  
Compares bike rental demand across different days, highlighting differences between holidays and regular days.

---

### 🔹 Temperature Variations
![Temperature Variations](Images/Temperature%20Variations.png)

**Description:**  
Visualizes the relationship between temperature changes and bike rental demand.

---

### 🔹 Weather Conditions
![Weather Conditions](Images/Weather%20Conditions.png)

**Description:**  
Analyzes bike demand across different weather conditions to understand weather impact on user behavior.

---

## 🛠 Tableau Implementation
- Connected cleaned dataset directly to Tableau
- Validated correct data types for dates, measures, and dimensions
- Built individual worksheets before combining them into dashboards
- Used **SUM** and **AVG** aggregations for analysis
- Added filters and dashboard actions for interactive exploration

---

## 💡 Key Insights
- Bike demand peaks during specific morning and evening hours
- Seasonal patterns significantly influence rental volume
- Weather and temperature have a clear impact on usage
- Holiday demand differs from regular working days

---

## 📦 Final Output
An interactive Tableau dashboard that enables stakeholders to explore bike-sharing demand dynamically and supports data-driven operational planning.

---

## 🚀 How to View the Dashboard
1. Download the `.twbx` file from the `Tableau/` folder  
2. Open it using **Tableau Public** or **Tableau Desktop**

---
