# 🚆 UK Train Rides Analysis (Maven Analytics Challenge) - Power BI Dashboard

## Overview
This Power BI dashboard provides an interactive analysis of UK train rides, focusing on performance metrics, customer trends, and operational insights with 32k Transactions. The dashboard is designed to help stakeholders understand key patterns in train travel data.

## 📊 Key Objectives

- Analyze average journey duration and delays by operator and route.
- Identify the most profitable and high-traffic routes.
- Explore travel behavior across different months and days.
- Determine factors influencing delays and trip efficiency.

  
## 📁 Dataset Overview

# Railway Ticket Sales Data Description
- **Transaction ID**: Unique identifier for each transaction.
- **Date of Purchase**: The date when the ticket was purchased (format: YYYY-MM-DD).
- **Time of Purchase**: The time when the ticket was purchased (format: HH:MM:SS).
- **Purchase Type**: Method of purchase (e.g., Online, Station).
- **Payment Method**: Payment type used (e.g., Contactless, Credit Card, Debit Card).
- **Railcard**: Type of railcard used (e.g., Adult, Disabled, Senior, None).
- **Ticket Class**: Class of the ticket (e.g., Standard, First Class).
- **Ticket Type**: Type of ticket (e.g., Advance, Off-Peak, Anytime).
- **Price**: Cost of the ticket in GBP.
- **Departure Station**: Station where the journey begins.
- **Arrival Destination**: Station where the journey ends.
- **Date of Journey**: Scheduled date of the journey (format: YYYY-MM-DD).
- **Departure Time**: Scheduled departure time (format: HH:MM:SS).
- **Arrival Time**: Scheduled arrival time (format: HH:MM:SS).
- **Actual Arrival Time**: Actual arrival time (format: HH:MM:SS), if available.
- **Journey Status**: Status of the journey (e.g., On Time, Delayed, Cancelled).
- **Reason for Delay**: Reason provided for any delay (e.g., Signal Failure, Weather Conditions).
- **Refund Request**: Indicates whether a refund was requested (Yes/No).

  ## Key Dataset Insights
- The dataset includes transactions for various routes, such as London Paddington to Liverpool Lime Street, London Kings Cross to York, and Manchester Piccadilly to Liverpool Lime Street.
- Ticket prices vary based on factors like class, type, and route.
- Some journeys were delayed or cancelled due to reasons like signal failures, weather conditions, or technical issues.
- Refund requests were made for certain delayed or cancelled journeys.
  
## Dashboard Components

### 1. **Key Metrics Overview**
   - Total tickets sold
   - Average ticket price
   - On-time performance rate
   - Refund request rate
   - Most popular routes

### 2. **Time-Based Analysis**
   - Daily/Monthly ticket sales trends
   - Peak purchase hours
   - Journey frequency by time of day

### 3. **Route Performance**
   - Route popularity heatmap
   - Delay frequency by route
   - Average delay duration
   - Cancellation reasons breakdown

### 4. **Customer Insights**
   - Railcard usage distribution
   - Ticket class preferences
   - Payment method trends
   - Purchase channel analysis (Online vs Station)

### 5. **Financial Analysis**
   - Revenue by ticket type
   - Price distribution across routes
   - Refund impact analysis

## Key Findings
1. **Peak Travel Times**: Highest ticket sales occur during weekday mornings (7-9 AM) and evenings (4-6 PM).
2. **Route Performance**: The London Kings Cross to York route shows the highest frequency of delays, primarily due to signal failures.
3. **Customer Preferences**: 
   - 68% of tickets sold are Standard class
   - Contactless payments account for 45% of transactions
4. **Financial Insights**: 
   - Advance tickets generate 60% of total revenue despite lower prices
   - First class tickets have the highest average price but lowest sales volume

## Technical Details
- **Last Updated**: January 2024
- **Visualizations Used**: 
  - Interactive maps
  - Time-series charts
  - Heatmaps
  - Donut and bar charts
  - KPI cards

## Potential Applications
- Operational planning for train operators
- Pricing strategy optimization
- Resource allocation decisions
- Customer service improvements
- Infrastructure investment planning
---

## 🛠️ Tools Used

- **Power BI**: Interactive dashboards and storytelling
- **Power Query**: Data cleaning and transformation
- **DAX**: Custom measures and calculations

---

## 📈 Dashboard Highlights

Key visuals and insights presented in the Power BI dashboard:

- 🚂 **Top 10 Routes by Revenue**
- ⏱️ **Average Journey & Delay Time by Operator**
- 📅 **Monthly and Daily Travel Trends**
- ⚠️ **Delay Frequency Distribution**
- 💷 **Revenue vs Distance Analysis**

---

## 📷 Sample Dashboard View

<img src="https://github.com/matrukan/UK-Train-Ride-Analysis/blob/main/UK_Train_Ride_Analysis_Dashboard_Preview.png?raw=true" width="450">
*Note: Actual dashboard contains interactive elements not shown in static screenshot*
---

## 🚀 How to Run This Project

Follow these steps to explore and interact with the UK Train Rides Analysis:

1. **Clone the Repository**  
   Download or clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/uk-train-rides-analysis.git
2. **Open the Power BI File**
   Open the UK Train Rides Analysis.pbix file in Power BI Desktop.

3. **Load the Dataset**
   Ensure that the railway.csv file is in the same folder as the .pbix file, or update the data source path in Power BI if needed.

4. **Explore the Dashboard**
   Use slicers, filters, and visuals to explore insights such as:

   Most delayed routes

   Highest revenue operators

   Monthly travel trends

   Delay analysis

5. Customize or Extend
   - Modify visuals, create new DAX measures, or transform the data further using Power Query.
     
## Dashboard Tips
1. **Filters**: Use the interactive filters to focus on specific time periods, routes, or ticket types.
2. **Tooltips**: Hover over visualizations to see detailed information.
3. **Drill-Down**: Click on elements to drill down into more specific data (e.g., click on a route to see its monthly performance).
4. **Cross-Filtering**: Selections in one visualization will filter data in others.

## 📌 Future Enhancements

Here are some potential improvements and extensions that could be added to this project:

- 🔄 **Real-time Data Integration**  
  Connect to live UK rail APIs to monitor real-time delays and schedules.

- 📡 **Weather Data Analysis**  
  Integrate historical weather data to analyze its impact on train delays and journey times.

- 🧠 **Predictive Modeling**  
  Use machine learning to forecast delays or passenger volumes based on historical patterns.

- 📈 **Enhanced Visuals**  
  Add animated visuals or drill-through pages in Power BI for deeper insights.

- 🗺️ **Geospatial Analysis**  
  Use map visuals to show routes, regional traffic, and delays geographically.

- 🧾 **Passenger Satisfaction Metrics**  
  Incorporate customer feedback or satisfaction scores if available.

- 🔍 **Advanced DAX Measures**  
  Create more complex KPIs like on-time performance percentage, revenue per mile, or load factor.

