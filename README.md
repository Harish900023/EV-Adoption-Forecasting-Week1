# 🚗 EV Adoption Forecasting - Week 1

This project is part of the AICTE Virtual Internship for July 2025 under the topic **EV Vehicle/Charging Demand Prediction**.

## 📌 Objective

To build a machine learning model that forecasts the adoption of Electric Vehicles (EVs) using historical data related to vehicle registrations by county and date.

---

## 📁 Files Included

| File Name                                 | Description                                |
|------------------------------------------|--------------------------------------------|
| `EV_Adoption_Forecasting_CodeOnly.ipynb` | Google Colab notebook with all the code    |
| `Electric_Vehicle_Population_By_County.csv` | Dataset used for training & testing     |

---

## 🔧 Workflow Overview

1. Loaded the EV population dataset.
2. Cleaned the data (handled missing values and outliers).
3. Performed EDA (Exploratory Data Analysis).
4. Used IQR method to remove outliers from `Percent Electric Vehicles`.
5. Built and trained a **Random Forest Regressor** model.
6. Evaluated model using **MSE** and **R² Score**.
7. Visualized predictions vs actual values.

---

## 📊 Model Performance

- **Model Used**: RandomForestRegressor
- **Metric**: Mean Squared Error (MSE), R² Score
- **Results**: Output varies per run but shows clear upward EV adoption trend.

---

## 🙋‍♂️ Improvisations Done by Me

- Handled missing dates and invalid data types.
- Treated outliers using the IQR method.
- Used Random Forest for improved prediction over linear models.
- Improved visualizations for better insight into prediction accuracy.

---

## 📅 Submission

This repository is submitted as **Week 1 milestone** for the AICTE Virtual Internship 2025.

