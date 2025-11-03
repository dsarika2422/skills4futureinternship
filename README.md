Climate Risk Prediction for Agriculture
AI-Based Crop Suitability and Climate Hazard Forecasting
Project Overview
This project focuses on predicting agricultural risks related to climate change such as droughts.
The goal is to recommend suitable crops for different regions based on climate conditions like rainfall and temperature.
The system supports sustainable agriculture and food security.
Objectives
Analyze historical rainfall, temperature, and agricultural production data.
Predict drought or climate-related risk levels.
Recommend crops that are suitable for the predicted climate conditions.
Visualize crop suitability and risk using geographic maps.
Problem Statement
Due to unpredictable climate changes, farmers often face crop failure and financial loss.
This model helps identify alternative resilient crops based on climatic risk, improving long-term sustainability.
Dataset Details
Primary Dataset (Kaggle):
Search on Kaggle: Indian Agriculture Dataset (1997–2021)
Dataset includes:
Region: State, District
Crop type
Rainfall data
Temperature data
Production and Area cultivated
Optional Additional Data:
NASA climate forecasting data
Drought Index (e.g., SPEI)
Methodology
Data Preprocessing
Clean missing values and outliers
Prepare climate and yield features
Modeling
Models used may include:
Random Forest or XGBoost → Crop Suitability Prediction
Logistic Regression or SVM → Drought Risk Classification
ARIMA or LSTM → Rainfall Forecasting
Visualization
Create risk maps and crop suitability maps
Tools: GeoPandas, Folium, Shapefiles
Outputs
Drought or climate risk classification for each region
Recommended crops based on risk and climate conditions
GIS-based visualization of high, medium, and low-risk zones
Trend analysis of climate variables
Tech Stack
Python
Pandas, NumPy
Scikit-learn, XGBoost
Matplotlib, Plotly
GeoPandas, Folium
Market Relevance
Supports precision agriculture and climate resilience
Aligns with sustainable agriculture innovations
Useful for policymakers, farmers, and AgriTech companies
Future Enhancements
Soil health factors like pH and moisture
Real-time monitoring with IoT sensors
Deployment as a farmer-facing mobile or web application
