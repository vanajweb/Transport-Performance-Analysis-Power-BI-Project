# Power BI Project: Transport  Performance Analysis Dashboard

## 📌 Overview
This project analyzes a transport fleet dataset using **Microsoft Power BI** to track operational performance, fuel efficiency, and costs.

## 📂 Dataset Description
**Columns:**
- Date – Trip date
- Vehicle_ID – Unique identifier for each vehicle
- Route – Route taken
- Distance_km – Distance traveled in kilometers
- Idle_Time_hr – Total idle time in hours
- Fuel_Liters – Fuel consumed in liters
- Goods_Weight_kg – Weight of goods transported (kg)
- Fuel_Cost_INR – Fuel cost (INR)

## 🛠 DAX Measures Created
- Avg Fuel Efficiency (km/l) = Distance / Fuel
- Fuel Cost per km (INR/km) = Fuel Cost / Distance
- Distance per kg (km/kg) = Distance / Goods Weight
- Estimated Driving Time (hr) = Distance / 60
- Idling Time (%) = Idle Time / Driving Time * 100
- Total Distance, Total Fuel, Total Fuel Cost, Total Goods Weight, Total Idle Time

## 📊 Visualizations
- KPI Cards: Total Distance, Fuel, Fuel Cost, Avg Fuel Efficiency
- Bar Chart: Fuel Cost per Route
- Line Chart: Fuel Efficiency Trends
- Pie Chart: Goods Weight Distribution
- Column Chart: Distance vs Fuel Consumption
- Table: Vehicle Performance Metrics

## 📈 Insights
- Identify cost-heavy routes.
- Track trends in fuel efficiency.
- Optimize routes for better load and fuel usage.

## 📎 Files Included
- `Transport_Performance_Dashboard_Project.pbix` – Power BI project file
- `Sample_Dashboard_Screenshot.png` – Dashboard preview
- `sample_transport_dataset.csv` 
- `README.md` – Project documentation

---
🔹 **Author:** Vanaj Kumar Yadav  
🔹 **Tools Used:** Microsoft Power BI, DAX
