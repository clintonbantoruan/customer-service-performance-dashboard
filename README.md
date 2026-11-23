# Customer Service Performance Dashboard

## Project Overview

This project focuses on analyzing customer service performance using Microsoft Excel. The dashboard provides an interactive overview of customer support activities, including ticket volume, ticket categories, ticket status, response time, resolution time, and agent performance.

The objective of this project is to transform raw customer service data into meaningful insights that can help monitor service performance, identify trends, and support data-driven decision-making.

## Dashboard Preview

![Customer Service Performance Dashboard](<img width="1051" height="535" alt="customer_service_dashboard" src="https://github.com/user-attachments/assets/89cb06e7-c8b9-47db-874b-0781c4c616a6" />
)

## Dataset Description

The dataset used in this project is simulated data created for learning and portfolio purposes. It contains **1,200 customer service records** covering the period from **January 2025 to November 2026**.

The dataset includes the following information:

- Ticket ID
- Created Date
- Customer ID
- Customer Age
- Product
- Ticket Type
- Priority
- Channel
- Ticket Status
- Assigned Agent
- First Response Hours
- Resolution Hours
- Satisfaction Rating

## Tools & Technologies

- **Microsoft Excel** – Data cleaning, data preparation, analysis, and dashboard development.
- **PivotTable** – Summarizing and analyzing customer service data.
- **PivotChart** – Visualizing ticket trends and performance metrics.
- **Excel Formulas** – Calculating key performance indicators (KPIs).
- **Slicers** – Creating interactive dashboard filters.

## Data Preparation

The data preparation process includes:

1. Reviewing the raw dataset.
2. Checking data quality and identifying missing values.
3. Checking duplicate Ticket IDs.
4. Preparing the cleaned dataset for analysis.
5. Adding a Year column to support time-based analysis.

Missing values in Resolution Hours and Satisfaction Rating are retained because they represent information that is not yet available for certain ticket statuses.

## Key Performance Indicators (KPIs)

The dashboard includes six main KPIs:

| KPI | Description |
|---|---|
| Total Tickets | Total number of customer service tickets |
| Resolved Tickets | Number of tickets with Resolved status |
| Pending Tickets | Number of tickets with Pending status |
| Average Response Time | Average time taken to respond to tickets |
| Average Resolution Time | Average time taken to resolve tickets |
| Customer Satisfaction | Average customer satisfaction rating |

## Dashboard Analysis

The dashboard provides four main analytical views:

1. **Ticket Volume Analysis** – Identifies monthly ticket volume trends.
2. **Ticket Category Analysis** – Shows the distribution of tickets by category.
3. **Ticket Status Analysis** – Provides an overview of ticket statuses.
4. **Agent Performance Analysis** – Compares agents based on average first response time.

Interactive slicers allow users to filter the dashboard by Year, Priority, and Channel.

## Key Findings

Based on the current dataset:

- A total of 1,200 customer service tickets were recorded.
- 806 tickets were resolved.
- 145 tickets remained pending.
- The average first response time was approximately 3.74 hours.
- The average resolution time was approximately 20.72 hours.
- The average customer satisfaction rating was approximately 3.82 out of 5.

These findings provide an overview of customer service performance within the simulated dataset.

## Project Files

- `Customer_Service_Performance_Dashboard.xlsx` – Main Excel dashboard and analysis.
- `data/Customer_Service_Performance_Dashboard_Data.xlsx` – Original dataset.
- `images/customer_service_dashboard.png` – Dashboard preview.
- `Project_Documentation.pdf` – Project documentation.

## Disclaimer

This project uses simulated data and is intended for educational purposes and portfolio demonstration only. It does not represent the actual operational performance of any company.

## Author

**Clinton Lumbantoruan**

Information Systems Graduate  
Universitas Teknokrat Indonesia
