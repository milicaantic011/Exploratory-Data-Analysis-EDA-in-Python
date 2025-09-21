# Airline Delays Exploratory Data Analysis

**An in-depth exploratory data analysis of U.S. airline delays comparing December 2019 vs December 2020 performance using Python data analysis libraries.**

---

## Project Overview

This project analyzes airline delay patterns in the United States, focusing on the comparison between **December 2019** (pre-pandemic) and **December 2020** (during pandemic) to understand how COVID-19 impacted flight operations.

---

##  Dataset Description

| **Attribute** | **Details** |
|--------------|------------|
| **Source** | [Kaggle Airline Delays Dataset](https://www.kaggle.com/) |
| **Timeframe** | December 2019 and December 2020 |
| **Scope** | U.S. domestic flights |
| **Records** | 3,351 flight records |

### **Key Features:**
- `arr_flights` — Total arrival flights
- `arr_del15` — Flights delayed by 15+ minutes
- `carrier_ct` — Carrier-related delays
- `weather_ct` — Weather-related delays
- `nas_ct` — National Airspace System delays
- `security_ct` — Security-related delays
- `late_aircraft_ct` — Late aircraft delays
- `arr_cancelled` — Cancelled flights
- `arr_diverted` — Diverted flights

---

##  Tech Stack

| **Component** | **Technology** |
|--------------|---------------|
| **Language** | Python 3.11 |
| **Environment** | Jupyter Notebook |

### **Libraries Used:**
- **`pandas`** — Data manipulation and analysis
- **`numpy`** — Numerical computing
- **`plotly`** — Interactive visualizations
- **`os`** — File system operations
- **`dash`**- Web 

---

## Analysis Goals

1. **Delay Pattern Analysis**  
   Identify main contributors to flight disruptions

2. **Carrier Performance Comparison**  
   Compare delay performance across different airlines

3. **Geographic Analysis**  
   Explore delay patterns across U.S. airports

4. **Pandemic Impact Assessment**  
   Compare 2019 vs 2020 flight operations

5. **Root Cause Analysis**  
   Determine primary causes of delays and cancellations

---

## 💡 Key Insights

The analysis explores:
- **Pandemic Impact**: How COVID-19 affected flight volumes and delay patterns
- **Carrier Performance**: Which airlines had best/worst on-time performance
- **Geographic Patterns**: Delay hotspots across U.S. airports
- **Delay Causes**: Relative impact of weather, carrier issues, system delays, etc.

---

## 📈 Key Visualizations

### **1. Correlation Matrix Heatmap**
![Correlation Heatmap](correlation_heatmap.png)

Visual analysis of relationships between different delay types, flight volumes, and cancellations to identify patterns and dependencies.

### **2. Top Airlines by Delay Rate**
![Airlines Delays](airlines_delays.png)

Comparative ranking of carriers based on percentage of delayed flights, showing the top 10 airlines with highest delay rates.

### **3. Top Airports by Delay Rate**
![Airports Delays](airports_delays.png)

Geographic analysis identifying the most problematic airports with highest delay percentages across the U.S.

### **4. Delay Types Distribution**
![Delay Types Pie Chart](delay_types_pie.png)

Pie chart showing the distribution of delay causes including carrier issues, weather, NAS, security, and late aircraft arrivals.

```
--

airline-delays-analysis/
│
├── airline_delay.csv                      # Source data
├── airline_delays_eda.ipynb               # Main analysis notebook
├── correlation_heatmap.png                # Correlation matrix visualization
├── airlines_delays.png                    # Airlines ranking visualization
├── airports_delays.png                    # Airports ranking visualization
├── delay_types_pie.png                    # Delay types distribution
├── visualizations/                        # Folder with HTML interactive versions
│  
└── README.md                               # Project documentation

---
```

## Author
Milica Antic

GitHub: @milicaantic011
LinkedIn: Milica Antic

## License
This project is licensed under the MIT License.

## Acknowledgments

Data source: Kaggle Airline Delays Dataset
Inspiration: Impact of COVID-19 on aviation industry
Tools: Plotly for interactive visualizations


Last Updated: September 2025




