# 🌍 Predicting Air Quality Levels using Machine Learning

This project utilizes machine learning algorithms to predict Air Quality Index (AQI) based on various environmental pollutant features. The goal is to provide actionable environmental insights by analyzing data collected from multiple Indian cities.

## 📁 Dataset

The dataset used is `city_day.csv`, available in a ZIP file format (`city_day.csv.zip`), containing daily pollutant concentrations and AQI values.

## 📊 Features

- PM2.5
- PM10
- NO, NO2, NOx
- NH3
- CO
- SO2
- O3
- Benzene, Toluene, Xylene
- City (Encoded)
- Date (parsed but not used in the model)

## ✅ Project Workflow

1. 📦 Upload and extract the dataset
2. 🧹 Preprocess the data (handle missing values, encode cities)
3. 🧠 Train an XGBoost Regressor model
4. 📉 Evaluate using MAE, MSE, and R² score
5. 📈 Visualize actual vs predicted AQI

## 🔧 Model Used

- XGBoost Regressor
- Evaluation Metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

## 📌 How to Run in Google Colab

1. Open the Colab notebook.
2. Upload `city_day.csv.zip` using the upload button.
3. Run each cell sequentially.
4. The final cell will show a scatterplot comparing predicted and actual AQI values.

## 📎 Requirements

These libraries are required (automatically installed in Colab):

```bash
pandas
scikit-learn
xgboost
matplotlib
seaborn
