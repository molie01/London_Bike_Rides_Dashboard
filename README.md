# 🚴‍♂️ London Bike Rides Dashboard (Tableau)

<p align="center">
  <img width="1000" src="https://capsule-render.vercel.app/api?type=waving&color=B2A3C7&height=200&section=header&text=London%20Bike%20Rides%20Insights%20%7C%20Tableau%20Dashboard&fontSize=35&fontColor=000000&fontAlign=50&fontAlignY=35&desc=Uncovering%20Urban%20Cycling%20Trends%20to%20Support%20Data-Driven%20City%20Planning&descAlign=50&descAlignY=55&animation=fadeIn">
</p>


## 🎯 Project Objective
Analyze London’s bike ride activity across weather conditions and time to uncover factors influencing usage, providing actionable insights for transportation planning.

---

## 🗂 Dataset Overview
- **Source**: [London bike rides dataset](https://github.com/molie01/London_Bike_Rides_Dashboard/blob/main/London%20Bike%20Rides%20Dataset.xlsx)
- **Fields**: Date, Temperature, Wind Speed, Time, Count (Number of Bike Rides per day), Season, Holiday, Weekday, Moving Averages

---

## ❓ Key Business Questions Answered
- What is the total number of bike rides recorded in the selected timeframe?
- How do temperature and wind speed influence rider behavior?
- Which hour of the day consistently sees the highest bike usage?
- What are the peak and off-peak periods for riding activity?
- How does ridership differ on weekends and holidays compared to weekdays?
- Can moving averages help identify seasonal or weather-related trends?
- What impact do weather shifts have on daily usage patterns?
- Which filters (e.g. duration, time range) reveal the most useful insights?
- How can these findings inform transportation planning and bike infrastructure?
- Dashboard Interaction [View Dashboard](#dashboard)

---

## 🛠 Process Overview
- Cleaned and preprocessed data using **Python (Pandas)** and exported to Excel for Tableau visualization
- Applied calculated columns for **hour of time**, **moving averages**, and **in-range filters**
- Designed dashboards in **Tableau** using slicers, filters, and heatmaps for visual storytelling
- Enabled dynamic moving average calculations (e.g., day, week, month) with customizable duration inputs to uncover temporal trends and support strategic analysis

---

## 📊 <a id="dashboard">Dashboard Preview</a>

[🔗 Download Tableau Dashboard (.twb)](https://github.com/molie01/London_Bike_Rides_Dashboard/blob/main/London%20Bike%20Rides%20Dashboard.twb)

[🔗 Interact Tableau Dashboard Online (.tableau.com)](https://public.tableau.com/app/profile/molie.nguyen/viz/LondonBikeRides_17497793484320/Dashboard1?publish=yes)

<p align="center">
  <img src="https://github.com/molie01/London_Bike_Rides_Dashboard/blob/main/Dashboard.png" width="800" alt="London Bike Rides Dashboard">
</p>

---

## 🔍 Key Insights
- **Over 19.9 million bike rides** were recorded in the dataset, reflecting widespread and sustained use of bike transportation across London.
- **Ride activity consistently peaks during morning and evening hours**, aligning with commuter traffic patterns.
- **Moderate temperatures (5°C–15°C)** and **low wind speeds** result in the highest ride volumes, while adverse weather discourages usage.
- **Weekend and holiday patterns** show more balanced usage across the day, indicating a shift toward recreational rides.
- The dashboard leverages **dynamic moving averages** (day/week/month) and flexible filters to reveal deep temporal patterns.
- These insights can help inform **infrastructure planning**, **bike fleet optimization**, and **weather-adaptive operational decisions** for urban mobility strategies.

---

## 📌 Final Conclusion
This project demonstrates how data visualization and analysis can turn raw transportation data into meaningful insights for decision-makers. By exploring weather, time, and usage patterns of over 19 million bike rides, the dashboard highlights key behaviors and trends that can support smarter infrastructure planning, improve operational efficiency, and enhance the urban cycling experience in London. 

---

## 🧰 Tools Used
- **Python** (Pandas for data preprocessing)
- **Microsoft Excel** (intermediate formatting for Tableau)
- **Tableau Public** (interactive dashboard design and analysis)

> 🚀 Designed to support data-driven decisions around transport infrastructure and urban mobility initiatives.
