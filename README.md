# 🚕 NYC Taxi Trip Duration Analysis

## 📌 Project Overview
This project performs an end-to-end exploratory data analysis (EDA) on the NYC Taxi Trip Duration dataset (`NYC.csv`) to understand time-based demand patterns and trip behavior in urban transportation.

The dataset contains **1.45M+ taxi trips** with detailed information about pickup time, vendor, and trip duration.

The main objective is to identify:

- Peak and off-peak demand hours  
- Weekly demand patterns  
- Trip duration behavior  
- Monthly and seasonal trends  

---

## 🧹 Data Cleaning
The following preprocessing steps were applied:

- Converted `pickup_datetime` to datetime format for time-based analysis  
- Extracted temporal features (hour, weekday, month)  
- Converted `trip_duration` from seconds to minutes  
- Removed outliers:
  - Trips shorter than 1 minute  
  - Trips longer than 120 minutes  
- Verified dataset integrity after cleaning  

---

## 📊 Exploratory Data Analysis
The analysis includes:

- Hourly demand analysis (trip count by hour)  
- Weekly demand comparison (weekday vs weekend)  
- Monthly trend analysis  
- Average trip duration by hour  
- Trip duration distribution analysis  
- Vendor-based performance comparison  

---

## ⏱️ Time-Based Analysis

A dedicated time-based analysis was performed to understand demand behavior:

### Key Findings

- Demand peaks during evening hours, reflecting typical commuting patterns  
- Early morning hours show the lowest activity levels  
- Demand increases toward the end of the week  
- Trip durations remain relatively stable throughout the day  

These patterns highlight the importance of time-driven operational planning.

---

## 🔥 Demand Patterns

- Strong variation in demand across hours of the day  
- Noticeable differences between weekdays and weekends  
- Heatmap analysis reveals concentrated demand during specific time windows  

This helps identify high-demand periods and optimize resource allocation.

---

## 📈 Visualizations

The project includes:

- Line chart for hourly demand trends  
- Bar charts for weekly and monthly patterns  
- Histogram for trip duration distribution  
- Heatmap for hour vs weekday demand  
- Bar chart for vendor comparison  

---

## 🛠️ Technologies Used

- Python  
- pandas  
- matplotlib  
- seaborn  

---

## 🚀 Conclusion

This analysis provides valuable insights into taxi demand behavior and operational efficiency in NYC.

Key opportunities include:

- Optimizing fleet allocation based on peak demand hours  
- Reducing operational costs during low-demand periods  
- Aligning driver schedules with weekly demand patterns  
- Improving efficiency for short-distance trips  
- Leveraging time-based insights for smarter dispatching  

---
