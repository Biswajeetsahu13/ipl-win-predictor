# 🏏 IPL Win Predictor

A Machine Learning project that predicts the **winning probability of an IPL match** based on current match conditions such as score, overs, wickets, and target.

This project uses **Logistic Regression with a Scikit-Learn Pipeline** and is deployed using **Streamlit** to create an interactive dashboard.

---

## 📊 Features

- Predicts **win probability in real time**
- Uses **match data from IPL datasets**
- Interactive **Streamlit dashboard**
- Shows **match progression**
- Clean machine learning pipeline
---
## 🧠 Machine Learning Model

Algorithm used:

- Logistic Regression

Pipeline steps:

1. Data preprocessing
2. Feature engineering
3. One-Hot Encoding for categorical variables
4. Logistic Regression model training
5. Probability prediction

Model accuracy: **~80%**

---

## 📂 Project Structure
ipl-win-predictor
│
├── app.py # Streamlit web application
├── pipe.pkl # Trained machine learning model
├── matches.csv # IPL dataset
├── Untitled.ipynb # Model training notebook
├── match_progression.py # Match analysis functions
└── README.md # Project documentation
