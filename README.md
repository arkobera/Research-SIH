# Electricity Crisis in Delhi: EDA & Solution Development

## Overview

This repository contains the exploratory data analysis (EDA) performed for the project aimed at solving the electricity crisis in Delhi. The goal of the project is to provide a comprehensive solution that involves energy demand forecasting, energy profiling, and predictive maintenance for transformers.

### Proposed Solution:

1. **Energy Demand Forecasting:** 
   - Forecasting electricity demand based on historical data, weather conditions, and other related features.
  
2. **Energy Profiling:**
   - Forecasting energy production from various sources such as renewable and non-renewable energy. 

3. **Predictive Maintenance:**
   - Introducing sensors to transformers to monitor their performance in real-time, and detecting issues to prevent failure due to aging infrastructure.

## Dataset and Features

The dataset used in this project includes:
- **Energy Drawal (MWh):** The amount of energy consumed.
- **Energy Injection (MWh):** The amount of energy produced.
- **Exempted RE Injection (MWh):** Energy production from renewable sources.
- **Loss (MWh) and Loss Percentage (%):** Energy loss in transmission.
- **Weather Data:** Historical temperature and other relevant weather data were fetched from external APIs.

## EDA Summary

The EDA explores several key aspects, including:

- **Seasonal Trends:**
  - Analysis of electricity demand patterns over time.
  - Investigating the seasonal nature of energy production and consumption.
  
- **Loss Analysis:**
  - Identifying the major contributors to energy loss in the system.
  
- **Renewable Energy Growth:**
  - Examining the rise in renewable energy production and its impact on filling the energy gap.

- **Energy vs Temperature:**
  - Correlating energy consumption with temperature changes to forecast periods of peak demand.

### Key Insights:
- Consumption increases significantly during summer due to cooling needs.
- Energy loss increases with higher production, requiring efficient infrastructure upgrades.
- Renewable energy is steadily increasing but has not yet consistently filled the demand gaps during peak consumption times.

## Challenges

- **Data Availability:** Gaps in historical data for certain periods required interpolation.
- **Predictive Modeling:** Forecasting long-term energy needs requires reliable external data (e.g., weather forecasts).
- **Scalability:** Incorporating predictive maintenance for a large number of transformers requires significant infrastructure.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/arkobera/Research-SIH.git
