  Traffic Prediction using Machine Learning
 Project Overview

This project focuses on predicting traffic volume using Machine Learning techniques based on time and location features. The model analyzes traffic patterns and helps estimate the number of vehicles in a given area at a specific time.

 Dataset

The dataset contains traffic sensor data with the following features:

DateTime
Junction
Vehicles
ID

From DateTime, additional features are extracted:

Hour
Day
Month
  Machine Learning Model
Algorithm: Random Forest Regressor
Task: Regression (predicting number of vehicles)
Target: Vehicles
 Workflow
Data Loading
Data Cleaning
Feature Engineering
Visualization
Model Training
Prediction
Evaluation (R² Score)
  Visualizations

The project includes:

Traffic by Hour
Traffic by Junction
Real vs Predicted values
Correlation Heatmap
   Results

The model predicts traffic volume with good accuracy using R² score.
