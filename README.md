# Neural-Network-Project
Porter Neural Networks: Delivery Time Prediction Model

# Overview
This project aims to build a regression model for Porter, India’s largest intra-city logistics marketplace, to predict delivery times for orders. Accurate delivery time predictions enhance customer satisfaction, improve resource allocation, and optimize delivery routing. Leveraging machine learning and neural networks, this project focuses on analyzing a rich dataset of delivery records and deriving actionable insights.

# Objectives
- Develop a machine learning model to estimate delivery times based on features like order details, restaurant location, and delivery partner data.
- Provide actionable insights to improve operational efficiency and customer experience.

# Data Highlights
The dataset includes:

- Features such as market ID, store categories, order details, and partner availability.
- Over 197,000 records detailing delivery metrics and associated attributes.
- Preprocessing steps to clean and encode data, handle missing values, and scale inputs for model training.

# Models
Random Forest Regressor:

# Achieved metrics:
- Mean Squared Error (MSE): 1294.48
- Root Mean Squared Error (RMSE): 35.98
- Mean Absolute Error (MAE): 12.85
- Observed significant room for improvement in capturing relationships between features and targets.


# Neural Networks:

Architecture:
- Input layer with 11 nodes
- Two hidden layers with 32 nodes each using ReLU activation
- Output layer with a linear activation for continuous target prediction
- Performance Metrics:
- MSE: 1297.74
- RMSE: 36.02
- MAE: 13.25

# Observations:
- Slightly better performance with optimization opportunities through hyperparameter tuning and feature engineering.

# Key Features
- Preprocessing: Feature engineering, handling missing data, and scaling using Min-Max normalization.
- Visualization: Heatmaps, bar plots, and scatter plots to explore correlations and identify trends.
- Model Evaluation: Comparison of Random Forest and Neural Network models to identify improvement areas.

# Recommendations
- Explore deeper architectures or advanced models like CNNs or RNNs for temporal and categorical data.
- Optimize hyperparameters using techniques like grid search.
- Enhance data quality and include additional predictive features.

# Impact
This project provides a framework for delivering actionable insights into delivery time predictions, supporting real-time routing adjustments, workload balancing, and better customer communication.
