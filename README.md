### Hotel Booking Cancellations – Machine Learning Project
## 📌 Overview

This project analyzes hotel booking data to understand and predict booking cancellations.
By performing data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling, the notebook provides insights into customer behavior and builds predictive models for cancellations.

The project is part of GTC ML Project 1.

## 📂 Dataset

Source: Hotel Booking Demand Dataset (UCI)
Rows: ~119,000 bookings
Target variable: is_canceled (1 = booking canceled, 0 = booking completed)
# Features include:
Hotel type (City/Resort)
Lead time
Number of guests
Booking channel
Market segment
Country
Special requests
And more...
## 🔑 Key Steps

# Data Preprocessing
Handle missing values
Encode categorical variables
Standardize/scale numerical features

# Exploratory Data Analysis (EDA)
Distribution plots
Correlation heatmaps
Boxplots of key features vs cancellations

# Feature Engineering
Standardizing country codes
Creating new derived features (e.g., stay duration)

# Modeling
Train/test split with stratification

# Dimensionality Reduction (optional)
PCA for visualization and efficiency

## 📊 Results
Target distribution: ~72.5% non-canceled, ~27.5% canceled bookings
PCA reduced optimal components ≈ 14

# 📜 License
This project is licensed under the MIT License.
