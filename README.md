# flight-price-prediction
End-to-End ML pipeline for flight price prediction
# ✈️ Flight Price Prediction

## Project Overview
End-to-end machine learning pipeline to predict Indian domestic
flight prices based on airline, route, duration, and stops.

**Project ID:** PRCP-1025  
**Name:** Hamza Siddiqui  
**Type:** Supervised Learning — Regression  

## Problem Statement
Flight ticket prices are highly dynamic and unpredictable.
This project uses machine learning to predict flight prices
based on historical data.

## Dataset
- Source: Flight Fare Dataset
- Records: 10,683 rows × 11 columns
- Target Variable: Price (INR)

## Features Used
- Airline, Source, Destination
- Date of Journey, Departure Time, Arrival Time
- Duration, Total Stops, Route

## Project Structure
- Feature Engineering — extracted date, time, duration features
- Encoding — Ordinal for Total_Stops, One-Hot for rest
- Models Trained — Random Forest, Extra Trees, 
  Gradient Boosting, XGBoost, Decision Tree

## Model Performance

| Model | R2 Score | RMSE |
|---|---|---|
| Extra Trees Tuned | 0.923 | 1290 |
| XGBoost Tuned | 0.917 | 1333 |
| Gradient Boosting Tuned | 0.900 | 1462 |
| Random Forest Tuned | 0.896 | 1493 |

## Final Model
**Extra Trees Tuned** — R2 Score: 0.923

## Libraries Used
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost, lightgbm
