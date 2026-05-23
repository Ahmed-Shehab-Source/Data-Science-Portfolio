# 🚗 Used Car Market Price Prediction Model

## 📌 Project Overview
This project delivers a robust machine learning regression pipeline engineered to predict the market valuation of used vehicles. Utilizing an extensive dataset encompassing over 371,000 distinct secondary automotive market listings, the architecture extracts complex nonlinear correlations between physical wear, odometer readings, and model age cohorts.

## ⚡ Core Insights & Engineering Deliverables
* **Data Engineering & Outlier Resilience:** Built a modular data processing pipeline using **KNN Imputation** to systematically handle missing descriptive variables, alongside **Robust Scaling** transforms to safeguard models against extreme price and high-performance engine outliers.
* **Model Optimization:** Evaluated several baseline linear and non-linear regression algorithms, deploying a **Random Forest Regressor** that achieved a dominant **R-squared score of 88%**, effectively cutting Mean Absolute Error (MAE) by 52% relative to baseline benchmarks.
* **Feature Importance:** Isolated vehicle mileage and registration year as the primary pricing factors, proving they account for over 70% of total asset depreciation variance.

## 📂 Execution Path
1. Run `pip install -r requirements.txt` to resolve structural dependencies.
2. Open and run `used_car_price_prediction.ipynb` to execute the data pipeline, train the estimators, and generate the residual performance analytics.
