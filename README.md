# Ride Demand Analytics & Forecasting Platform

This project implements an end-to-end analytics and forecasting solution to analyze ride demand patterns and predict future demand using Azure-style analytics workflows.

## Tech Stack
- Python (Pandas, NumPy, Statsmodels)
- SQL
- Azure Synapse (simulated using SQL)
- Azure Data Factory (logical ETL flow)
- Power BI

## Architecture
Raw Ride Data → SQL Analytics → Forecasting Model → Power BI Dashboard

## Key Features
- Demand trend analysis by hour, location, and day
- Time-series forecasting using ARIMA
- Business-ready KPIs for fleet planning

## How to Run
1. Load CSV into SQL database
2. Run SQL scripts for aggregation
3. Execute Python notebook for forecasting
4. Visualize results in Power BI
