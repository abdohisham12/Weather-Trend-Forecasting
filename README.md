# Weather Forecasting Project

## Overview
This project demonstrates the use of machine learning models to forecast essential weather parameters, such as **temperature**, **pressure**, and **humidity**. By analyzing data from the **'World Weather Repository'** on Kaggle, we uncovered insights into weather trends and developed predictive models with high accuracy.

### Key Objectives:
- Predict key weather metrics with high precision.
- Explore and visualize trends in weather data.
- Conduct advanced analyses, such as anomaly detection and feature importance.

---

## Features

### Data Preprocessing
- **Cleaning:** Addressed missing values and outliers for reliable data quality.
- **Feature Engineering:** Added derived features like **daytime duration** and **feels-like temperature** to improve prediction accuracy.
- **Normalization:** Used Min-Max Scaling and transformations for consistent data representation.

### Exploratory Data Analysis (EDA)
- **Trends:** Seasonal variations in temperature and humidity identified.
- **Correlations:** Strong relationship between temperature and humidity uncovered.
- **Geospatial Analysis:** Regional differences visualized using maps.

### Machine Learning Models
- **XGBoost:** Achieved **R² = 0.91**, effective for general predictions.
- **SVR (Support Vector Regressor):** Achieved **R² = 0.98**, excellent for time series predictions.
- **Random Forest:** Provided insights into feature importance with general R² score of **0.87**.
- **LightGBM:** Provided results for each target, focusing on one at a time.

### Advanced Analyses
- **Anomaly Detection:** Identified unusual weather patterns.
- **Feature Importance:** Highlighted critical factors influencing predictions.
- **Climate Impact Insights:** Explored environmental trends.

---

## Dataset
The dataset contains comprehensive weather data, including:
- **Weather Metrics:** Temperature (°C), Pressure (mb), Humidity, Wind Speed.
- **Air Quality Metrics:** PM2.5, PM10, Ozone, Carbon Monoxide.
- **Astronomical Data:** Sunrise, Sunset, Moonrise, Moon Phase.

Source: [World Weather Repository on Kaggle](https://www.kaggle.com/).

---

## How to Use

### 1. Clone the Repository
Clone the project to your local machine using the following command:
```bash
git clone https://github.com/abdohisham12/weather-forecasting.git
cd weather-forecasting
```

### 2. Run the Analysis
- Use Jupyter notebook provided to explore data and perform analysis.
- Execute scripts in the folder to preprocess data and train machine learning models.

## Results

### Model Performance:
| Model          | R² Score |
|----------------|----------|
| XGBoost        | 0.91     |
| SVR            | 0.98     |
| Random Forest  | 0.87     |

### Insights:
- **Seasonal Trends:** Strong seasonal patterns observed in temperature and humidity.
- **Correlations:** Significant relationship between temperature and humidity metrics.
- **Regional Variations:** Location-specific differences highlight the importance of regional adjustments in modeling.

---

## Future Work

### Model Improvements:
- Explore advanced models such as LSTM and VAR for time series forecasting.
- Perform hyperparameter tuning to enhance model performance.

### Real-Time Integration:
- Extend the project to include real-time weather data for live predictions.

### Additional Features:
- Integrate more environmental factors to improve the accuracy and scope of predictions.

---
