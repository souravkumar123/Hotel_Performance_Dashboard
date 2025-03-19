# 🏨 Hotel Performance Dashboard - Power BI

## 📌 Overview
This **Hotel Performance Dashboard** is built in Power BI to analyze key metrics related to hotel occupancy, revenue, and overall performance. The dashboard provides insights into occupancy rates, revenue per available room (RevPAR), average daily rate (ADR), booking trends, and key property performance indicators.

## 📊 Features
- 🔄 **Dynamic Filtering**: Filter by city, room type, and date range.
- 📈 **Key Performance Indicators (KPIs)**: Revenue, Occupancy Rate, ADR, and Realization %.
- 🏢 **Category-Based Occupancy Analysis**: Business vs. Luxury category occupancy.
- 📉 **Trend Analysis**: Weekly performance trends of RevPAR, ADR, and Occupancy %.
- 🌐 **Booking Platform Analysis**: Realization % and ADR trends across different booking platforms.
- 🏨 **Property Performance Metrics**: RevPAR, Occupancy %, ADR, Cancellations %, and Customer Ratings for each property.

## 📂 Data Sources
The dashboard is built using data from:
- 🏨 **Hotel Booking Systems**: Daily room bookings, revenue, and occupancy data.
- 🌍 **Third-Party Booking Platforms**: MakeMyTrip, Tripster, Direct Online, etc.
- 📊 **Property Management Systems (PMS)**: Hotel property-level financial and operational data.

## 📌 Key Metrics Explained
| 📏 Metric          | 📖 Description                                      |
|----------------|------------------------------------------------|
| **💰 RevPAR**     | Revenue per Available Room                     |
| **🏷️ ADR**        | Average Daily Rate                             |
| **🛏️ DSRN**       | Daily Sellable Room Nights                     |
| **📅 DBRN**       | Daily Booked Room Nights                       |
| **🏠 DURN**       | Daily Utilized Room Nights                     |
| **📊 Realization %** | Percentage of revenue realized from bookings |
| **📈 Occupancy %**  | (Occupied Rooms / Total Available Rooms) * 100 |
| **❌ Cancellations %** | Percentage of canceled bookings            |
| **⭐ Avg. Rating**  | Average customer rating per property          |

## 🚀 How to Use the Dashboard
1. 📥 **Download and Open the Power BI File (.pbix).**
2. 🎛️ **Select Filters**: Choose city, room type, or date range to customize insights.
3. 📊 **Analyze KPIs**: Review revenue, occupancy, and ADR at a glance.
4. 🔍 **Drill Down**: Click on charts for deeper insights by category and platform.
5. 🏨 **Compare Properties**: Use the Property Key Metrics table to compare hotel performance.

## 🛠️ Tech Stack
- 🖥️ **Power BI**: Data visualization and dashboard development.
- 🧮 **DAX (Data Analysis Expressions)**: KPI calculations and data modeling.
- 🗄️ **SQL (Optional)**: Used for preprocessing and data extraction.
- 📂 **Excel/CSV**: Data sources for initial input.

## 📁 Included Files
The following dataset files are included:
- 📅 **dim_date.csv**
- 🏨 **dim_hotels.csv**
- 🛏️ **dim_rooms.csv**
- 📊 **fact_aggregated_bookings.csv**
- 📑 **fact_bookings.csv**

## 🔮 Future Enhancements
- 🔄 **Real-time Data Integration** using APIs.
- 🤖 **Machine Learning Forecasting** for hotel occupancy.
- 🗣️ **Guest Sentiment Analysis** from reviews.
- 📧 **Automated Email Reports** for hotel managers.



