# 🚦 Traffic Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting **traffic volume (number of vehicles)** using Machine Learning techniques. The model analyzes historical traffic sensor data and learns patterns based on time and location features to estimate traffic conditions.

The goal is to support smart transportation systems and improve traffic management efficiency.

---

## 👤 Author
- Name: Your Name  
- Group: Your Group  

---
# 📽️ Presentation Slides
👉 [Click here to view project slides](https://docs.google.com/presentation/d/1LXQDZGZF_a7s7tFkrAfK9tWHMinJYnZn/edit?usp=drive_link&ouid=103493244324584131487&rtpof=true&sd=true)

---

## 📊 Dataset Description
The dataset contains traffic sensor records with the following columns:

- **DateTime** → Timestamp of the record  
- **Junction** → Road intersection ID  
- **Vehicles** → Number of vehicles (target variable)  
- **ID** → Unique identifier for each record  

### 🔧 Feature Engineering
From the `DateTime` column:
- Hour  
- Day  
- Month  

---

## 🎯 Problem Statement
Predict the number of vehicles (**traffic volume**) based on:

- Junction  
- Hour  
- Day  
- Month  

This is a **regression problem**.

---

## 🤖 Machine Learning Model
- Algorithm: Random Forest Regressor  
- Type: Supervised Learning (Regression)  
- Target Variable: Vehicles  

---

## ⚙️ Workflow
1. Load dataset  
2. Data cleaning  
3. Feature engineering  
4. Exploratory Data Analysis (EDA)  
5. Data visualization  
6. Train-test split  
7. Model training  
8. Prediction  
9. Model evaluation  

---

## 📊 Visualizations
- Traffic trends by hour  
- Traffic distribution by junction  
- Correlation heatmap  
- Real vs predicted values  

---

## 📈 Model Evaluation
The model is evaluated using:

- **R² Score** → prediction accuracy  
- **Mean Squared Error (MSE)** → error measurement  

👉 Higher R² = better performance  

---
-

## 🚀 Future Improvements
- Deep Learning (LSTM for time series)  
- Real-time traffic prediction system  
- Streamlit web application  
- Smart city integration  

---



## 📌 Note
This project demonstrates a complete machine learning pipeline including data preprocessing, visualization, model training, and evaluation applied to transportation data.
