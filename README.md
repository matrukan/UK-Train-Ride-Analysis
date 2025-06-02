# 🚆 UK Train Rides Analysis (Maven Analytics Challenge)

This project analyzes train ride data from the UK, using the dataset provided by **Maven Analytics** for a data storytelling challenge. The objective is to uncover meaningful insights about the UK railway system, covering aspects such as route performance, delay patterns, revenue generation, and travel trends over time.

---

## 📁 Dataset Overview

# Railway Ticket Sales Data Description

## Overview
This dataset contains records of railway ticket transactions, including details about purchases, journeys, and customer information. The data spans from December 8, 2023, to January 3, 2024, and includes various attributes such as purchase methods, ticket types, journey statuses, and more.

## Columns Description

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

## Key Insights
- The dataset includes transactions for various routes, such as London Paddington to Liverpool Lime Street, London Kings Cross to York, and Manchester Piccadilly to Liverpool Lime Street.
- Ticket prices vary based on factors like class, type, and route.
- Some journeys were delayed or cancelled due to reasons like signal failures, weather conditions, or technical issues.
- Refund requests were made for certain delayed or cancelled journeys.

## Example Use Cases
- Analyzing peak purchase times and popular routes.
- Investigating the impact of delays on customer satisfaction (refund requests).
- Comparing revenue generated from different ticket types (Advance, Off-Peak, Anytime).

## Data Source
The data is synthetic and generated for demonstration purposes.

---

## 📊 Key Objectives

- Analyze average journey duration and delays by operator and route.
- Identify the most profitable and high-traffic routes.
- Explore travel behavior across different months and days.
- Determine factors influencing delays and trip efficiency.

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

*You can add a screenshot here once you generate the dashboard:*

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

6. (Optional) Publish to Power BI Service
   Publish the report to your Power BI workspace to share and schedule updates.

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

- 📤 **Power BI Service Deployment**  
  Deploy the report to Power BI Service for online access and scheduled refreshes.

- 🔍 **Advanced DAX Measures**  
  Create more complex KPIs like on-time performance percentage, revenue per mile, or load factor.


