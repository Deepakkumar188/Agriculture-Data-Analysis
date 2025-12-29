# 🌾 Agricultural Data Analytics System
### Crop Performance Analysis using Python

A Python-based data analytics project that analyzes agricultural crop performance across Indian states using production, climate, and economic parameters. The system converts raw agricultural data into meaningful insights through statistical analysis and visualizations.


## 📌 Project Overview

Agriculture is a key pillar of India’s economy, yet many farming decisions are made without structured data analysis.  
This project aims to bridge that gap by building a **data-driven analytics system** that evaluates crop yield, profitability, and risk across different regions and years.

Instead of complex machine learning models, this project focuses on **descriptive analytics, clarity, and visualization**, making insights easy to understand and interpret.

---

## 🎯 Objectives

- Analyze multi-year agricultural data across different Indian states  
- Calculate yield per hectare and farmer profitability  
- Study the impact of climate factors on crop performance  
- Identify high-risk and low-risk agricultural regions  
- Present insights through professional visualizations  
- Write clean, modular, and scalable Python code  

---

## 📊 Dataset Summary

- **States Covered:** Punjab, Uttar Pradesh, Maharashtra, Madhya Pradesh, Tamil Nadu, Rajasthan  
- **Years:** 2021 – 2023  
- **Crops:** Wheat, Rice  
- **Records:** 18 (prototype dataset)

### Data Parameters
- Cultivated Area (hectares)
- Production (tonnes)
- Rainfall (mm)
- Temperature (°C)
- Cultivation Cost (INR/hectare)
- MSP (INR/tonne)
- Market Price (INR/tonne)

---

## 🛠️ Technology Stack

- **Programming Language:** Python 3.8+
- **Libraries Used:**
  - pandas – data manipulation
  - numpy – numerical computation
  - matplotlib – data visualization
  - seaborn – statistical visualization
- **IDE:** VS Code / Jupyter Notebook
- **OS:** Windows / Linux / macOS

---

## 🧩 System Architecture

The project follows a **pipeline-based architecture**:

```

Raw Data
↓
DataFrame Creation
↓
Feature Engineering
↓
Statistical Analysis
↓
Visualization & Insights

```

### Key Modules
1. **Data Ingestion**
2. **Feature Engineering**
3. **Analysis Engine**
4. **Visualization Engine**

---

## 🧮 Key Calculations

### Yield per Hectare
```

Yield = Production / Area

```

### Net Profit
```

Cost per Tonne = Cultivation Cost / Yield
Net Profit = (Market Price − Cost per Tonne) × Yield

```

### Classification
```

Profit → Net Profit > 0
Loss   → Net Profit ≤ 0

```

---

## 📈 Visualizations Included

The system generates **8 professional charts**:

1. Bar Chart – State-wise yield comparison  
2. Line Chart – Yield trends over time  
3. Scatter Plot – Rainfall vs yield relationship  
4. Histogram – Profit and loss distribution  
5. Box Plot – Profitability variance (risk)  
6. Area Chart – Cumulative production trends  
7. Heatmap – Multi-parameter risk matrix  
8. Pie Chart – Overall profit vs loss ratio  

All charts follow a **dark theme** for clarity and presentation quality.

---

## 🔍 Key Insights

- Punjab consistently shows the highest yield due to strong irrigation
- Maharashtra shows lower yield because of monsoon dependency
- Optimal rainfall range for better yield: **650–850 mm**
- High yield does not always mean high profit
- Around **65–70% scenarios are profitable**
- Some states face high income variability, indicating higher risk

---

## 🧪 Testing & Performance

- Manual validation of yield and profit calculations
- Edge-case handling (division by zero)
- All visualizations render without errors
- Execution time: **< 2 seconds**
- Memory usage: **< 100 MB**

---

## ⚠️ Limitations

- Small dataset (prototype scale)
- Only two crops included
- Annual average climate data
- No web or mobile interface yet

---

## 🚀 Future Enhancements

### Short-Term
- Add more crops and states
- Extend dataset to 10+ years
- Include soil quality parameters

### Medium-Term
- Web dashboard using Flask + React
- Predictive models (regression)
- Live weather API integration

### Long-Term
- Cloud deployment (AWS/Azure)
- Mobile app for farmers
- Machine learning-based yield forecasting
- GIS and satellite data integration

---

## 📂 Project Structure

```
Project/
│
├── agricultural_analytics.py
├── README.md
├── requirements.txt
└── output/
├── yield_comparison.png
├── rainfall_vs_yield.png
├── profit_distribution.png
└── other_charts.png

