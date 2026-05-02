🏠 Airbnb Price Analysis & Prediction (NYC Dataset)
📌 Overview

This project focuses on exploratory data analysis (EDA) and predictive modeling using the NYC Airbnb dataset. The goal is to analyze listing data, uncover pricing patterns, and build a model to predict Airbnb prices based on key features.

🎯 Objectives
Perform data cleaning and preprocessing on real-world dataset
Analyze pricing trends using visualizations
Identify key factors influencing Airbnb prices
Build a regression model to predict listing prices
📊 Dataset
Source: NYC Airbnb Open Data (Kaggle)
Contains information about listings such as:
Location (neighbourhood, borough)
Room type
Price
Reviews and availability
🧹 Data Cleaning
Removed irrelevant columns: id, name, host_name, last_review
Handled missing values in reviews_per_month
Converted categorical variables using one-hot encoding
Removed non-numeric columns for modeling
📈 Exploratory Data Analysis
Analyzed price distribution (right-skewed with outliers)
Compared prices across room types
Studied location-based pricing trends
Examined feature relationships using correlation heatmap
🔍 Key Insights
Manhattan listings are the most expensive
Entire homes/apartments have significantly higher prices
Price distribution is highly skewed with some extreme values
Location and room type are the strongest factors affecting price
Reviews do not strongly influence pricing
🤖 Model Building
Model Used: Linear Regression
Features prepared using encoding techniques
Target variable: price
📊 Model Evaluation
Evaluated using:
Mean Absolute Error (MAE)
R² Score
Model captures general pricing trends but struggles with extreme values due to outliers
📌 Conclusion
Location and room type play a major role in Airbnb pricing
EDA revealed clear patterns and business insights
Linear Regression provides baseline predictions
Real-world data complexity highlights the need for advanced models

👉 This project demonstrates practical skills in data cleaning, analysis, visualization, and machine learning.

🛠 Tools & Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
👉 This project demonstrates practical skills in data cleaning, analysis, visualization, and machine learning.

🛠 Tools & Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
