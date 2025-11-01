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
