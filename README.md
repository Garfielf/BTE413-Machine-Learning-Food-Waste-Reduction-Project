# BTE413-Machine-Learning-Food-Waste-Reduction-Project
Food waste reduction optimized with machine learning techniques. 

Food Waste Prediction ML Project
Predicting Surplus Food Quantities and Product Popularity for TooGoodToGo-style Platforms
Project Overview
This machine learning project addresses food waste in restaurants by predicting:

Surplus Quantity (Regression): How much food will be left over each day

Product Popularity (Classification): Which items will be in high/medium/low demand

Business Problem
Food waste reduction platforms lack predictive optimization

Restaurants struggle to predict surplus food quantities

Inconsistent availability frustrates customers

Missed revenue opportunities from poor demand forecasting

Technical Implementation
Dataset
5,000 records across 50 restaurants

20 features including restaurant type, weather, day of week, meal type

2 target variables: surplus_qty (regression), popularity_class (classification)

Models Developed
Random Forest Regressor (Surplus Prediction)

RMSE: 1.20 items

R² Score: 0.9987

Cross-validation: 99.59% ± 0.50%

Random Forest Classifier (Popularity Prediction)

Accuracy: 97.5%

F1-Score: 0.98 (weighted average)

Cross-validation: 97.17% ± 0.51%

Key Features
waste_efficiency: Most important predictor (41% importance)

demand_pressure: Second most important (32% importance)

inventory_prepared: Third most important (26% importance)

Business Impact
Financial Projections (Annual)
Cost Savings: $810,026 from waste reduction

Revenue Increase: $7,458,659 from better demand prediction

Total Economic Impact: $8,268,685

ROI: 5,412% with 0.2-month payback period

Environmental Impact
CO₂ Reduction: 73,639 kg annually

Food Waste Reduction: 44,183 kg annually

Files Generated
restaurant_food_waste_dataset.csv - Synthetic training data

surplus_prediction_model.pkl - Trained regression model

popularity_classification_model.pkl - Train
