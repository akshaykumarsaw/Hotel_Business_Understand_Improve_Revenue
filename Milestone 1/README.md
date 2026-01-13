# Hotel Revenue Analysis – Milestone 1

## Project Overview
This project focuses on understanding and improving hotel revenue using data modeling and visualization techniques in Power BI.  
The objective is to analyze bookings, revenue, occupancy, and profitability using a star schema model.

## Dataset Description
The dataset contains hotel booking and operational data, including:
- Booking dates and seasons
- Room revenue and occupancy rates
- ADR and RevPAR metrics
- Cost and profit-related fields
- Guest and booking information

Source: Provided CSV dataset 

## Data Modeling
A star schema was designed with:
- Fact Table: Bookings
- Dimension Tables:
  - Date
  - Room
  - Customer
  - Hotel Branches

## Data Transformations
Power Query was used to:
- Clean and format data types
- Create dimension tables
- Remove redundant columns
- Prepare fact and dimension tables for modeling

## Calculated Columns
The following calculated columns were created:
- Booking Duration
- Stay Type (Short, Medium, Long)
- Room Category (Economy, Premium, Luxury)

## Key Visualizations
- Revenue and Profit trend by Month
- Revenue distribution by Room Category
- Bookings by Stay Type
- Occupancy Rate by Season
- Interactive slicers for dynamic analysis

## Key Insights
- Revenue remains relatively consistent across months.
- Medium-stay bookings contribute the highest booking volume.
- Luxury and Economy room categories generate the highest revenue.
- Profit trends vary across months, highlighting cost impacts.

## Tools Used
- Power BI
- Power Query
- GitHub


