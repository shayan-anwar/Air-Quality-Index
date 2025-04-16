# Air-Quality-Index
## 📌 Overview

This repository contains code and resources for predicting global AQI categories (`Good`, `Moderate`, `Unhealthy`) based on key pollutants (PM2.5, O3, NO2, CO) and geographic information.

---

## 🧠 Objectives

- ✅ Collect and preprocess real-world AQI data
- 📊 Perform exploratory data analysis (EDA)
- 🌐 Visualize temporal and spatial trends in pollution
- 🧪 Apply statistical methods for significance testing
- 🤖 Train machine learning models for AQI prediction

---

## 📁 Dataset

- **Source:** [Kaggle - Global Air Pollution Data](https://www.kaggle.com/datasets/sazidthe1/global-air-pollution-data)
- **Key Features:**
  - Location: Country, City
  - AQI Value
  - Main Pollutants: PM2.5, O3, NO2, CO
  - AQI Category: `Good (0)`, `Moderate (1)`, `Unhealthy (2)`

---

## 🧹 Data Preprocessing

- Handled missing values using imputation/removal
- Removed duplicates and outliers (IQR method)
- Encoded AQI categories numerically
- Normalized continuous variables

---

## 📈 Exploratory Data Analysis

- Distribution of AQI by region and time
- Correlation between pollutants and AQI
- Summary statistics for pollutants and air quality

---

## 📊 Visualization

- Line plots: AQI trends over time
- Bar & pie charts: Distribution of AQI levels
- Scatter plots: Pollutant–AQI relationships
- Geographic maps: Global pollution visualization

---

## 📉 Statistical & Machine Learning Analysis

- Hypothesis testing (T-test, Chi-square)
- Regression (Linear, Multiple)
- Clustering (K-means)
- Classification Models:
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`, `folium`
- **Tools:** Jupyter Notebook, Google Colab
