#  Uber Trips Trend & Map Analysis

This project performs an end-to-end Exploratory Data Analysis (EDA) on the Uber trip dataset containing the following columns:
Date/Time | Lat | Lon | Base

The analysis aims to uncover **temporal patterns**, **week-wise trends**, **geospatial behavior**, and **statistical relationships** in Uber ride data.

---

## **Project Overview**
Uber generates thousands of ride logs daily. Understanding this data helps identify user demand patterns, peak hours, and location-based trends.  
This project uses Python to explore the dataset by analyzing **time-based trends**, **geospatial mapping**, and performing **statistical tests** like P-value distribution.

---

##  **Dataset Description**
The dataset contains the following columns:

| Column Name | Description |
|-------------|-------------|
| **Date/Time** | Date and time of the trip |
| **Lat** | Latitude of the pickup point |
| **Lon** | Longitude of the pickup point |
| **Base** | Uber base/company code |

---

##  **Key Steps Performed**

### ✔️ 1. Importing Required Libraries  
Using pandas, numpy, seaborn, matplotlib, folium, etc.

### ✔️ 2. Reading the Uber Dataset  
Loading CSV and converting Date/Time into useful components  
(hour, weekday, month, etc.).

### ✔️ 3. Visualizing the Uber Trips  
- Hourly trends  
- Daily/weekly analysis  
- Monthly patterns  

### ✔️ 4. Week-wise Trend Analysis  
Observed how Uber rides vary from **Monday to Sunday**.

### ✔️ 5. Geospatial Mapping  
Using **Folium** to plot pickup locations on an interactive map.

### ✔️ 6. P-value Distribution  
Performed statistical checks to understand relationships in the data.

### ✔️ 7. Relationship Analysis  
- Lat vs Lon  
- Hour vs Number of rides  
- Day of week vs Ride count  
- Base stations vs Trips  

---

##  **Visualizations**
The project contains:  
- Line plots  
- Heatmaps  
- Bar charts  
- Scatter plots  
- Interactive map (Folium)

These help in understanding patterns in both time and geography.

---
