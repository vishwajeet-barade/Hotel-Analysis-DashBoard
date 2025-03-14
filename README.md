# Hotel-Analysis-DashBoard

Hotel Analysis Dashboard - Power BI

Overview

This Power BI dashboard provides key insights into hotel performance, including revenue, occupancy rates, and booking trends. It enables data-driven decision-making for hotel management.

![image](https://github.com/user-attachments/assets/6b30a592-c5f0-407a-bb70-df1f25e1b0e1)

![image](https://github.com/user-attachments/assets/ee88b065-4fcf-48ae-9560-d6cff1d10abd)


Features

Revenue Analysis: Total revenue generated and revenue by city.

Booking Insights: Daily bookings, total bookings by platform, and booking status by month.

Occupancy Rates: Occupancy percentage by city, room class, and day type.

Trend Analysis: Revenue timeline for performance tracking.

Filtering Options: Day type, category, room class, city, and month.


Data Model

Fact Tables: fact_booking, fact_aggregated_booking

Dimension Tables: dim_hotels, dim_rooms, dim_date, custom_calendar

Relationships: Fact tables are linked to dimensions using keys like property_id, room_id, and date.


Technologies Used

Power BI for data visualization
Data Sources: Hotel booking datasets

Data Modeling: Star schema with fact and dimension tables


How to Use

Open the Power BI file.

Use filters to analyze hotel data by category, room class, city, and time.
