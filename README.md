# ⚡ U.S. State-Level Electricity Consumption Analysis and Forecasting

This project explores and forecasts electricity consumption trends across U.S. states using real-world data from the U.S. Energy Information Administration (EIA). It includes data cleaning, exploratory data analysis (EDA), visualization, and future forecasting using Facebook Prophet.

---

## 📊 Project Overview

- **Objective:** Analyze state-wise electricity consumption across years, identify patterns and outliers, and forecast future consumption to support data-driven energy policy and planning.
- **Data Source:** [U.S. EIA Open Data Portal](https://www.eia.gov/opendata/)
- **Time Range:** 2010–2021
- **Level:** Intermediate Data Analysis project with forecasting

---

## 🗃️ Dataset

- `EIA_State_Electricity_Expanded.csv`  
  Includes annual electricity consumption data by state in megawatt-hours (MWh), categorized by generation source and provider type.

---

## 🔍 Key Steps in the Project

### 1. Data Cleaning
- Removed non-state aggregates like “United States”
- Converted numeric columns to correct data types
- Scaled total consumption to millions of MWh

### 2. Exploratory Data Analysis (EDA)
- Box plots to identify outlier states in consumption
- Line charts showing national and top-state trends over time
- Labeled markers for better visual clarity

### 3. Forecasting
- Applied **Facebook Prophet** to forecast future consumption for California
- Visualized expected trends with uncertainty intervals

---

## 📈 Insights

- Certain states like California consistently consume high amounts of electricity.
- Outliers and unusual spikes were observed in small states due to reporting issues or anomalies.
- Forecasting shows steady growth in demand, indicating a need for capacity planning.

---

## ✅ Recommendations

- Prioritize energy efficiency programs in high-demand states.
- Use forecasts to guide infrastructure and renewable energy investments.
- Tailor policies based on regional consumption trends and seasonality.
- Improve state-level data consistency to enable better forecasting.

