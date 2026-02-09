# 🌍 AQI Prediction System

A Machine Learning–based web application to predict **Air Quality Index (AQI)** using pollutant concentration data.  
The app is built using **Streamlit** and compares different ML models for AQI prediction.

🔗 **Live App**:  
[https://aqi-prediction-system-9kjvneu4su63e7tltx7vz.streamlit.app](https://aqi-prediction-system-9jkyneu4su63e7tlxtx7vz.streamlit.app/)

---

## 📌 Features

- Predicts **AQI value** based on pollutant inputs
- Displays **AQI category** (Good, Moderate, Poor, etc.)
- Provides **health advisory messages**
- Interactive and **dark-themed UI**
- Deployed using **Streamlit Community Cloud**
- Supports **XGBoost model (stable)**

---

## 🧠 Machine Learning Models

### ✅ XGBoost (Currently Active)
- Trained on cleaned India AQI dataset
- Produces stable and accurate predictions
- Used directly for inference in the deployed app

### ⚠️ Random Forest (Experimental)
- Trained during development
- Faced inconsistency during deployment
- Temporarily disabled in the deployed version
- Will be fixed and re-enabled in future updates

> ℹ️ To ensure reliability, only the XGBoost model is exposed in the live app.

---

## 🧪 Input Parameters

The model takes the following pollutant concentrations:

- **PM2.5** (µg/m³)
- **PM10** (µg/m³)
- **NO₂** (µg/m³)
- **SO₂** (µg/m³)
- **CO** (mg/m³)
- **O₃** (µg/m³)
- **Month** (1–12)

---

## 📊 AQI Categories

| AQI Range | Category |
|---------|----------|
| 0–50 | Good |
| 51–100 | Satisfactory |
| 101–200 | Moderate |
| 201–300 | Poor |
| 301–400 | Very Poor |
| 401+ | Severe |

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **Scikit-learn**
- **XGBoost**
- **NumPy & Pandas**
- **Joblib**
- **Git & GitHub**

---

## 📁 Project Structure

