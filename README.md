# 🌫️ Air Quality Index Prediction using Facebook Prophet

This project leverages **Facebook Prophet**, a robust time series forecasting model, to predict the **Air Quality Index (AQI)** based on historical data from the [UCI Air Quality dataset](https://archive.ics.uci.edu/dataset/360/air+quality).  
By forecasting AQI levels, the model helps understand air quality trends and supports proactive environmental management.

---

## 🚀 Overview

Air Quality Index (AQI) is a crucial metric that communicates the quality of air to the public, indicating the level of pollution and its potential impact on health.  
Accurate forecasting of AQI helps anticipate pollution levels, enabling timely actions to mitigate exposure to harmful pollutants.

This project utilises **Facebook Prophet**, an open-source forecasting tool developed by Meta, designed to handle time series data with strong seasonal effects and other patterns.  
Prophet is particularly adept at handling missing data, outliers, and incorporating seasonal trends, making it suitable for forecasting AQI levels.

---

## 📊 Dataset

The dataset used in this project is the [UCI Air Quality dataset](https://archive.ics.uci.edu/dataset/360/air+quality), which contains 9,358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device.  
The device was located in a significantly polluted area at road level within an Italian city. Data were recorded from March 2004 to February 2005, representing one year of on-field deployment.

Ground truth hourly averaged concentrations for CO, Non-Methanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx), and Nitrogen Dioxide (NO2) were provided by a co-located reference certified analyzer. Missing values are tagged with a value of `-200`.

---
