🛒 Customer Purchase Prediction Dashboard
📌 Overview

This project predicts whether a customer session will lead to a purchase using Machine Learning, and visualizes insights with an interactive Power BI dashboard.

The goal is to help businesses understand customer behavior patterns, optimize marketing strategies, and improve conversion rates.

⚡ Key Features

✅ Machine Learning Model trained to predict purchase likelihood.

📊 Power BI Dashboard with clear business KPIs:

Total Sessions

Purchases

Conversion Rate

Model Accuracy

🔍 Feature Importance – which actions (e.g., add-to-cart, session duration) drive conversions.

📈 Actual vs Predicted Outcomes – model performance validation.

⏰ User Behavior Analysis: conversion by time of day & session duration.

📂 Project Structure
Customer-Purchase-Prediction/
│── data/                # Dataset (sessions, clicks, purchases, etc.)
│── notebooks/           # Jupyter/Colab notebooks for ML training
│── dashboard/           # Power BI dashboard files (.pbix)
│── images/              # Screenshots for README
│── README.md            # Project documentation

🧠 Tech Stack

Python (Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn)

Machine Learning: Logistic Regression 

Power BI for dashboard visualization

🚀 How It Works

Data Preprocessing

Cleaned and transformed customer session data.

Features: session_duration, pages_viewed, add_to_cart, checkout_initiated, etc.

Model Training

Built ML model to classify sessions as Purchase (1) or No Purchase (0).

Achieved ~99% accuracy (due to dataset balance, further tuning can be applied).

Visualization

Created Power BI dashboard to display model insights & business KPIs.

📊 Dashboard Preview
🔹 KPI Metrics

Total Sessions: Measure of traffic.

Purchases: Count of successful conversions.

Conversion Rate: Percentage of sessions that led to purchase.

Model Accuracy: Performance of the ML model.

🔹 Visuals

Feature Importance (ML Explainability)

Actual vs Predicted Results

Conversion Rate by Hour of Day

Conversion Rate by Session Duration

(Add screenshot here)


💡 Business Insights

⏰ Conversions peak between 10 AM – 12 PM, suggesting stronger purchase intent during mid-day.

⏳ Longer session durations strongly correlate with higher purchase probability.

🛒 Add-to-cart actions are the strongest predictor of conversion.
