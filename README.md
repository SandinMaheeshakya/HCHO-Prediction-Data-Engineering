# HCHO Prediction and Data Engineering

This project investigates the dynamics of formaldehyde (HCHO) pollution across Sri Lankan cities, analyzing its variations influenced by altitude, population density, and COVID-19 containment measures. It employs data engineering techniques, machine learning models, and spatio-temporal analysis to uncover patterns and predict future pollution levels.

## Introduction
Formaldehyde (HCHO) is a significant air pollutant with both environmental and health impacts. This project explores the factors driving HCHO pollution trends in Sri Lanka and utilizes predictive modeling to support better air quality management.

## Project Objectives
- Analyze HCHO pollution trends over time and across locations.
- Correlate HCHO levels with weather, altitude, population density, and human activities.
- Predict future HCHO levels using machine learning techniques.

## Dataset Description
The project uses a dataset containing:
- **Tropospheric HCHO Levels**: Daily readings from various Sri Lankan cities.
- **Weather Data**: Comprehensive weather data from 30 cities (2010–2023).
- **Population Data**: Population statistics of selected cities in 2024.

## Main Content of the Project
### Data Preprocessing
- **Null Value Handling**: Used LOCF and NOCB methods for filling missing values in time-series data.
- **Outlier Removal**: Managed using Interquartile Range (IQR).
- **Structural Validation**: Ensured consistency for machine learning model integration.

### Spatio-Temporal Analysis
- **Seasonal Trends**: Explored variations in HCHO levels during inter-monsoonal and monsoonal periods.
- **COVID-19 Lockdowns**: Assessed the impact of reduced human activity on air quality.
- **Altitude and Population Correlations**: Studied the effects of elevation and population density on pollution.

### Machine Learning Models
Time-series forecasting methods were applied:
- **SARIMA**: Chosen for its effectiveness in capturing seasonal patterns in HCHO data.
- **Model Evaluation**: Compared SARIMA with ARIMA and SARIMAX models for accuracy.

## Findings and Insights
1. HCHO levels are higher in urban areas due to industrial activities and traffic emissions.
2. Seasonal trends indicate higher levels during inter-monsoonal periods.
3. COVID-19 lockdowns significantly reduced HCHO levels in urban areas.
4. Predictions highlight potential future spikes in pollution, aiding mitigation planning.

---

This project contributes towards creating cleaner and healthier environments by advancing our understanding of air pollution trends and their underlying factors.
