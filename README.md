# 🚲 Seoul Bike Sharing Demand Analysis (Tableau)

## 📌 Project Goal

Analyze bike rental demand in **Seoul** to understand usage patterns across time, seasons, holidays, and weather conditions, and translate insights into actionable planning support for bike-sharing operations.

---

## 🏢 Business Problem

Bike-sharing systems face operational challenges such as:

* When to allocate more bikes
* How demand changes by hour, season, and holidays
* How external factors like weather impact rentals

This project focuses on identifying **when and why bike demand changes**, helping operators make data-driven decisions on bike availability and resource planning.

---

## 📂 Dataset

* **Source:** Seoul Bike Sharing dataset
* **Granularity:** Hourly rental data
* **Key Attributes:**

  * Date & Hour
  * Season
  * Holiday / Non-Holiday
  * Weather conditions (Temperature, Humidity, etc.)
  * Rented Bike Count

The dataset provides sufficient detail to perform time-based and condition-based demand analysis without extensive preprocessing.

---

## 🔗 Data Connection & Validation

* Connected the cleaned CSV dataset directly to **Tableau**
* Verified correct data types for dates, numeric measures, and categorical dimensions
* Ensured consistency in hourly and seasonal records to avoid aggregation errors

---

## 📊 Key Metric (KPI)

* **Total Rented Bike Count**
  Used as the primary KPI to measure overall bike-sharing demand across different dimensions.

---

## 🧩 Key Dimensions Analyzed

* Hour of Day
* Date
* Season
* Holiday vs Non-Holiday
* Weather Conditions

These dimensions enable granular analysis of demand fluctuations and user behavior.

---

## 📈 Visualizations & Dashboards

### 1️⃣ Hourly Demand Analysis

![Hourly Demand](Images/dashboard_1.png)

* Line chart showing bike demand by hour
* Clearly highlights **peak and off-peak usage hours**
* Useful for daily bike redistribution planning

---

### 2️⃣ Seasonal Demand Patterns

![Seasonal Demand](Images/dashboard_2.png)

* Bar chart comparing rentals across seasons
* Reveals strong **seasonal trends** affecting bike usage
* Helps anticipate high-demand and low-demand periods

---

### 3️⃣ Holiday vs Non-Holiday Usage

![Holiday Analysis](Images/dashboard_3.png)

* Bar chart comparing demand on holidays vs regular days
* Shows behavioral differences in bike usage
* Useful for adjusting weekend and holiday operations

---

### 4️⃣ Weather Impact on Demand

![Weather Impact](Images/dashboard_4.png)

* Scatter / line-based analysis of weather conditions vs demand
* Identifies how environmental factors influence ridership
* Supports proactive planning during adverse weather

---

## 🧠 Analysis Logic & Design Choices

* **Aggregations Used:** SUM and AVG
* **Calculated Fields:** Not required (dataset already well-structured)
* **Filters:** Season, Hour
* **Dashboard Actions:** Interactive filtering between charts

These choices keep the dashboards intuitive, responsive, and interview-friendly.

---

## 🔍 Key Insights

* Bike demand peaks during specific **commute hours**
* **Seasonality** plays a major role in rental volume
* Demand differs noticeably on **holidays vs non-holidays**
* Weather conditions have a measurable impact on ridership

---

## 🎯 Final Output

* Fully interactive **Tableau dashboards**
* Clear KPI-driven analysis
* Decision-support tool for operational planning

---

## 🛠 Tools Used

* Tableau
* Excel / CSV

---

## 🧑‍💼 Interview Summary

This project demonstrates:

* Business-oriented analytical thinking
* Strong Tableau dashboard design
* Ability to convert raw data into actionable insights

It can be clearly explained end-to-end in interviews, from business problem to visualization-driven insights.

---

📌 *Note: Tableau packaged workbook (.twbx) is available in the repository for direct interaction.*
