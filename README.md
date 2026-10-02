# Logistics Operations & Fleet Performance Analysis Dashboard

## Project Overview

An interactive **Logistics Operations & Fleet Performance Dashboard** developed in Power BI to analyze revenue, profitability, customer activity, route performance, driver activity, and vehicle maintenance costs.

The dashboard transforms operational logistics data into actionable business insights, helping stakeholders monitor financial performance, fleet costs, customer contribution, driver activity, and monthly revenue trends.

## Objective

The objective of this project is to provide a centralized analytical view of logistics operations and answer key business questions such as:

- How much revenue and profit is being generated?
- Which routes generate the highest revenue?
- Which customers contribute the most revenue?
- Which drivers handle the highest number of trips?
- Which trucks have the highest maintenance costs?
- How does revenue change throughout the year?
- Where are potential operational cost and performance opportunities?

## Key Performance Indicators

The dashboard tracks the following high-level KPIs:

| KPI | Value |
|---|---:|
| Total Revenue | $262.5M |
| Total Profit | $161.2M |
| Total Customers | 200 |

## Dashboard Features

### 1. Revenue & Profitability Overview

The KPI cards provide a high-level view of:

- Total Revenue
- Total Profit
- Total Customers

These metrics allow stakeholders to quickly understand the overall financial and customer performance of the logistics operation.

### 2. Revenue by City Route

The **Total Revenue by City Route** visualization compares revenue generated across different origin-destination routes.

Examples include:

- Philadelphia → Seattle
- Charlotte → Portland
- Phoenix → Philadelphia
- Columbus → Portland
- Seattle → Charlotte
- Columbus → Los Angeles

This analysis helps identify routes contributing significant revenue to the business.

### 3. Driver Trip Analysis

The **Total Trips by Drivers** visualization compares the number of trips completed by individual drivers.

This provides insight into driver workload and operational activity.

### 4. Truck Maintenance Cost Analysis

The **Total Maintenance Cost by Truck ID** chart identifies trucks with the highest maintenance expenditure.

This can support fleet management decisions and help identify vehicles requiring closer maintenance monitoring.

### 5. Customer Revenue Analysis

The **Total Revenue by Customer** visualization identifies customers generating the highest revenue.

This provides insight into customer contribution and helps identify key revenue-generating accounts.

### 6. Monthly Revenue Trend

The **Total Revenue by Month** visualization tracks monthly revenue throughout the year.

This helps identify:

- Revenue fluctuations
- High-performing months
- Lower-performing periods
- Potential seasonal patterns

## Interactive Filters

The dashboard includes interactive slicers for:

- **Year**
- **City Route**

These filters allow users to dynamically explore the operational and financial performance of specific periods and routes.

## Tools & Technologies

- **Microsoft Power BI**
- Power Query
- DAX
- Data Modelling
- Data Transformation
- Data Visualization
- Business Intelligence
- KPI Development

## Data Analysis & Modelling

The project involved working with multiple related logistics tables covering areas such as:

- Customers
- Loads
- Routes
- Trips
- Drivers
- Trucks
- Trailers
- Fuel Purchases
- Maintenance Records
- Delivery Events
- Safety Incidents

Relationships between these tables were established to create an analytical data model capable of supporting cross-functional logistics analysis.

## Key Analytical Questions

This project was designed to answer questions such as:

1. Which routes generate the highest revenue?
2. Which customers contribute the most revenue?
3. Which drivers complete the highest number of trips?
4. Which trucks incur the highest maintenance costs?
5. How does revenue fluctuate throughout the year?
6. How can logistics managers monitor fleet and operational performance?
7. Which operational areas may require further investigation?

## Key Insights

Based on the dashboard:

- Total revenue is approximately **$262.5 million**.
- Total profit is approximately **$161.2 million**.
- The dashboard contains **200 customers**.
- **Philadelphia → Seattle** is the highest-revenue route among the routes displayed.
- **First Group** is the highest-revenue customer among the customers displayed.
- **William Wilson** has the highest number of trips among the drivers displayed.
- **TRK000003** has the highest maintenance cost among the trucks displayed.
- Monthly revenue fluctuates throughout the year, indicating periods of stronger and weaker revenue performance.

> Note: The insights above reflect the data and selections visible in the dashboard. Results may change when different filters are applied.

## Skills Demonstrated

- Power BI
- DAX
- Power Query
- Data Modelling
- Data Transformation
- Data Cleaning
- Business Intelligence
- KPI Development
- Logistics Analytics
- Fleet Analytics
- Revenue Analysis
- Profitability Analysis
- Route Analysis
- Customer Analysis
- Driver Performance Analysis
- Maintenance Cost Analysis
- Time-Series Analysis
- Data Visualization
- Business Insight Generation

## Project Structure

```text
Logistics-Operations-Analysis-PowerBI/
│
├── README.md
│
├── Dashboard/
│   └── Logistics_Operations_Dashboard.pbix
│
├── Screenshots/
│   └── logistics-operations-dashboard.png
