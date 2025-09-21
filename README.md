#  Airline Delays Exploratory Data Analysis

**An in-depth exploratory data analysis of U.S. airline delays comparing December 2019 vs December 2020 performance using Python data analysis libraries.**

---

##  Project Overview

This project analyzes airline delay patterns in the United States, focusing on the comparison between **December 2019** (pre-pandemic) and **December 2020** (during pandemic) to understand how COVID-19 impacted flight operations.

## Dataset Description

| **Attribute** | **Details** |
|--------------|------------|
| **Source** | [Kaggle Airline Delays Dataset](https://www.kaggle.com/) |
| **Timeframe** | December 2019 and December 2020 |
| **Scope** | U.S. domestic flights |
| **Unit of Analysis** | Flights aggregated per carrier per U.S. city |

### **Key Features:**
- `arr_flights` — Total arrival flights
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

---

## Analysis Goals

1. **Delay Pattern Analysis**  
   Identify main contributors to flight disruptions

2. **Carrier Performance Comparison**  
   Compare delay performance across different airlines

3. **Geographic Analysis**  
   Explore delay patterns across U.S. cities

4. **Pandemic Impact Assessment**  
   Compare 2019 vs 2020 flight operations

5. **Root Cause Analysis**  
   Determine primary causes of delays and cancellations

---

## Key Insights

The analysis explores:
- **Pandemic Impact**: How COVID-19 affected flight volumes and delay patterns
- **Carrier Performance**: Which airlines had best/worst on-time performance
- **Geographic Patterns**: Delay hotspots across U.S. airports
- **Delay Causes**: Relative impact of weather, carrier issues, system delays, etc.

---

##  Key Visualizations

### **1. Correlation Matrix Heatmap**
Visual analysis of relationships between different delay types, flight volumes, and cancellations to identify patterns and dependencies

### **2. Top 10 Airlines by Delay Rate**
Comparative ranking of carriers based on percentage of delayed flights, highlighting best and worst performing airlines

### **3. Top 10 Airports by Delay Rate**
Geographic analysis identifying the most problematic airports with highest delay percentages across the U.S.

### **4. Interactive Plotly Dashboards**
Dynamic visualizations allowing users to filter by:
- Time period
- Carrier
- Delay type

Explore patterns and trends in real-time with interactive controls

### **5. Delay Cause Breakdown**
Pie charts and bar plots showing the distribution of delay causes:
- Weather conditions
- Carrier/airline issues
- National Airspace System (NAS)
- Security delays
- Late aircraft arrivals

---

##  Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/airline-delays-analysis.git

# Navigate to project directory
cd airline-delays-analysis

# Install required packages
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

##  Project Structure

```
airline-delays-analysis/
│
├── data/
│   ├── airline_delays_2019.csv
│   └── airline_delays_2020.csv
│
├── notebooks/
│   └── airline_delays_eda.ipynb
│
├── visualizations/
│   ├── correlation_heatmap.html
│   ├── top_airlines_delays.html
│   └── top_airports_delays.html
│
├── README.md
└── requirements.txt
```

---

## Results Summary

| **Metric** | **2019** | **2020** | **Change** |
|-----------|----------|----------|------------|
| Total Flights | XXX,XXX | XXX,XXX | -XX% |
| Avg Delay Rate | XX% | XX% | +X% |
| Top Delay Cause | Carrier | Weather | - |
| Most Delayed Airport | XXX | XXX | - |

---

##  Author

** Milica Antic**  
- GitHub: (https://github.com/milicaantic011)
- LinkedIn: (https://www.linkedin.com/in/milica-antic-ds/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Data source: Kaggle Airline Delays Dataset
- Inspiration: Impact of COVID-19 on aviation industry
- Tools: Plotly for interactive visualizations

---

*Last Updated: [21.09.2025.]*


