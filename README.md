# Airbnb Demand and Availability Forecasting – Amsterdam

## Project Overview

This project focuses on analyzing Airbnb data for Amsterdam to forecast booking demand and listing availability. The goal is to build a data-driven understanding of how property characteristics and seasonal trends influence booking outcomes.

## Work Summary

The project involved the following key steps:
- **Data Acquisition and Cleaning:** Loaded raw listings and calendar datasets, handled missing values, removed duplicates, and corrected data types for accurate analysis.
- **Exploratory Data Analysis (EDA):** Conducted descriptive analysis to uncover booking patterns, seasonality effects, and distribution of prices across different room types and neighborhoods.
- **Feature Engineering:** Created new variables to capture temporal patterns (e.g., month, day of week), host activity, and property features relevant to booking likelihood.
- **Data Visualization:** Used plots to illustrate booking trends, price distributions, and availability patterns over time and geography.
- **Model Building and Evaluation:** Developed machine learning models to predict booking likelihood.

## Machine Learning Models Used

Two classification models were built to predict whether a listing would be booked on a given day:
- **Random Forest Classifier:** A tree-based ensemble model used for its robustness and ability to handle nonlinear relationships.
- **Logistic Regression:** A statistical model used for binary classification with interpretability advantages.

**Modeling Steps:**
- Features were scaled using **StandardScaler**.
- Data was split into training and testing sets (70/30 split).
- Models were trained and evaluated using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Confusion matrices were plotted to visualize model performance.

## Skills and Tools Used

- Python (Pandas, NumPy) for data manipulation and cleaning.
- Matplotlib and Seaborn for data visualization.
- Scikit-learn for machine learning model building and evaluation.
- Feature engineering techniques to create meaningful predictors.
- Statistical analysis and business interpretation of trends.
- Data storytelling and presentation of findings through visuals and structured reporting.

## Business Relevance

Forecasting demand and availability helps hosts optimize their pricing and listing strategies to improve occupancy rates and maximize revenue. It also provides valuable insights for travelers to plan trips during less congested periods. Platform managers can use these insights for market analysis, policy design, and resource allocation.

## Datasets Used

- **Listings Dataset:** Detailed information about Airbnb properties including location, room type, pricing, and property features.
- **Calendar Dataset:** Daily availability and pricing data for each listing, enabling demand and booking trend analysis.
