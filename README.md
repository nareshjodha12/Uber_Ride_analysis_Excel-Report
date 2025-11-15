# 🚖 Uber Ride Data Analysis Dashboard (Excel-Based)

An interactive data analysis project built in **Microsoft Excel** to explore, 
analyze, and visualize Uber trip data. The dashboard provides comprehensive insights 
into ride performance across time, city, vehicle type, and more using pivot tables, slicers, 
charts, and conditional formatting.


## 📌 Project Overview

This project aims to analyze ride data from Uber trips including time patterns, vehicle preferences, payments, and geographic insights. The data was modeled and visualized entirely in Excel using pivot tables, custom DAX formulas, and charts to create an intuitive and interactive dashboard.


## 🧾 Data Source

- **Primary Sheet**: Uber trip data with columns:
  - `TripID`, `Pickup Time`, `Drop Off Time`, `Trip Time`, `Shift`, `Day`, `Time Slot`, `Passenger Count`, `Trip Distance`, `PULocationName`, `DOLocationName`, `City`, `Fare`, `Surge Fee`, `Total Fare`, `Vehicle`, `Payment Type`.

- **Lookup Sheet**: Mapping of `Location ID` → `Location` and `City`.


## 📊 Key Metrics and KPIs

| Metric | Description |
|--------|-------------|
| **Total Booking** | Count of unique trips |
| **Total Booking Value** | Total revenue generated from trips |
| **Average Booking Value** | Avg. fare per trip (includes surge fee) |
| **Total Trip Distance** | Sum of trip distances (miles) |
| **Average Trip Distance** | Mean trip distance |
| **Average Trip Time** | Avg. trip duration (minutes) |
| **Day vs Night Shift** | % split of rides taken in each shift |
| **Vehicle Type Breakdown** | Booking, revenue, and distance by vehicle (UberX, XL, Comfort, etc.) |
| **Payment Method Usage** | Share of payment types like Uber Pay, Cash, Google Pay, etc. |
| **Popular Pickup Zones** | Top pickup locations by trip count |
| **Trip Trend by Day & Time** | Weekly and hourly trip trends |


## 📌 Dashboards and Visualizations
<a href ="https://github.com/nareshjodha12/Uber_Ride_analysis_Excel-Report/blob/main/Screenshot%20-Uber-Analysis-dashboard.png"/>

### ✅ Dashboard Tabs

1. **Summary Overview**
   - Key KPIs for bookings, revenue, average distance & time
   - Day/Night shift breakdown
   - Time trend of bookings

2. **Trip Analysis**
   - Total bookings by city
   - Top 5 pickup zones
   - Vehicle and payment type distribution
   - Trips by time bins (e.g., 00:00 – 02:59)

3. **Performance Breakdown**
   - Vehicle-based booking value and distance
   - Payment method comparison
   - City-wise insights using slicers


## 📈 Visual Techniques Used

- Pivot Tables
- Slicers and Timelines
- Combo Charts (Bar + Line)
- Conditional Formatting
- Dynamic Ranges
- Lookup Relationships (Location ID to City Mapping)


## 🧠 Insights Derived

- **UberX** dominates with ~6,000+ trips and highest trip value contribution.
- Most trips occur during **day shift (68%)**, with a noticeable drop during night.
- **East Harlem South, Gramercy**, and **East Village** are popular pickup zones.
- Payment is largely dominated by **Uber Pay**, followed by **Cash** and **Google Pay**.
- Saturday and Sunday show peak booking trends.
- 12:00–17:59 is the busiest time window for trips.


## 🚀 Technologies Used

- Microsoft Excel (2021+)
- Pivot Tables
- Data Validation
- Excel Formulas (VLOOKUP, IF, SUMIFS)
- Excel Charts
- Custom Time Bucketing


## 📁 File Structure

```
├── UberExcel.xlsx
│   ├── Trip Data
│   ├── Location Mapping
│   ├── Summary Dashboard
│   └── Charts & KPIs
├── README.md
```


## 🧩 Future Enhancements

- Introduce charts for revenue per passenger group
- Integrate Power Query for automated data refresh
- Export to Power BI for more scalable visualization

## Dashboard
 ![Screenshot.png](https://github.com/nareshjodha12/Uber_Ride_analysis_Excel-Report/blob/main/Screenshot%20-Uber-Analysis-dashboard.png)




