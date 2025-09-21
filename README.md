Arline Delays Exploratory Data Analysis

An in-depth exploratory data analysis of U.S. airline delays comparing December 2019 vs December 2020 performance using Python data analysis libraries.


Project Overview

This project analyzes airline delay patterns in the United States, focusing on the comparison between December 2019 (pre-pandemic) and December 2020 (during pandemic) to understand how COVID-19 impacted flight operations.

Dataset Description

Source: Kaggle Airline Delays Dataset
Timeframe: December 2019 and December 2020
Scope: U.S. domestic flights
Unit of Analysis: Flights aggregated per carrier per U.S. city

Key Features:

arr_flights — Total arrival flights

carrier_ct — Carrier-related delays

weather_ct — Weather-related delays

nas_ct — National Airspace System delays

security_ct — Security-related delays

late_aircraft_ct — Late aircraft delays

arr_cancelled — Cancelled flights

arr_diverted — Diverted flights

Tech Stack
Language: Python

Libraries Used:

pandas — Data manipulation and analysis
numpy — Numerical computing
plotly — Interactive visualizations

Environment: Jupyter Notebook

Analysis Goals

Delay Pattern Analysis: Identify main contributors to flight disruptions
Carrier Performance Comparison: Compare delay performance across different airlines
Geographic Analysis: Explore delay patterns across U.S. cities
Pandemic Impact Assessment: Compare 2019 vs 2020 flight operations
Root Cause Analysis: Determine primary causes of delays and cancellations

Key Insights
The analysis explores:

How the pandemic affected flight volumes and delay patterns
Which carriers performed best/worst in terms of on-time performance
Geographic hotspots for delays and cancellations
The relative impact of different delay causes (weather, carrier, system, etc.)

Key Visualizations

Correlation Matrix Heatmap: Visual analysis of relationships between different delay types, flight volumes, and cancellations to identify patterns and dependencies
Top 10 Airlines by Delay Rate: Comparative ranking of carriers based on percentage of delayed flights, highlighting best and worst performing airlines
Top 10 Airports by Delay Rate: Geographic analysis identifying the most problematic airports with highest delay percentages across the U.S.
Interactive Plotly Dashboards: Dynamic visualizations allowing users to filter by time period, carrier, and delay type to explore patterns and trends in real-time
Delay Cause Breakdown: Pie charts and bar plots showing the distribution of delay causes (weather, carrier, NAS, security, late aircraft)


