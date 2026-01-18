# Flight Pricing & Route Analysis (2023)

An interactive Excel dashboard analyzing key **flight pricing KPIs** across airlines, departure times, number of stops, and departure cities using historical flight data.


##  Quick Navigation
- [Project Overview](#project-overview)
- [Business Questions](#business-questions)
- [Key KPIs](#key-kpis)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Dashboard Preview](#dashboard-preview)
- [Key Insights](#key-insights)
- [How to Use](#how-to-use)


##  Project Overview
This project focuses on understanding **flight pricing patterns and operational trends** by analyzing average ticket prices and flight volumes across multiple dimensions such as airlines, departure times, stops, and cities.

The goal was to build a **clear, business-focused Excel dashboard** that supports comparison-based analysis rather than raw data exploration.


##  Business Questions
- Which airlines have higher or lower average ticket prices?
- Which departure time slots have higher average ticket prices?
- How does the number of stops affect average ticket prices?
- Which airlines operate the highest number of flights?
- Which departure cities have higher average ticket prices over the 3-month period?
- Which departure cities have the highest number of flights?


##  Key KPIs
- Average Ticket Price  
- Total Number of Flights  
- Cheapest Average Route  
- Costliest Average Route   


## 🗂 Dataset
- Historical flight data (India)
- Url- https://www.kaggle.com/datasets/iamavyukt/goibibo-flight-data/data
- Time period: **3 months in 2023**
- Key fields:
  - Airline  
  - Departure City  
  - Arrival City  
  - Ticket Price  
  - Number of Stops  
  - Departure Time  
  - Flight Duration  

> Note: Duration and departure times were grouped into meaningful buckets to enable clearer analysis.


## Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Charts
  - Slicers
  - Helper columns for time, stop, and duration grouping


## 🔍 Key Insights
- Average ticket prices vary significantly across airlines.
- Flights with fewer stops generally have higher average prices.
- Morning departures tend to be priced higher on average.
- A small number of airlines account for a large share of total flights.
- Pricing and flight volume patterns differ notably by departure city.


## ▶️ How to Use
1. Open the Excel file.
2. Use slicers to filter by:
   - Departure City
   - Airline
   - Travel Class
   - Month
3. Interact with the dashboard to compare pricing and volume KPIs dynamically.



