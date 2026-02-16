#  Diabetes Prediction Web App

A Machine Learning web application built with **Streamlit** that predicts whether a person is at **risk of diabetes** based on medical attributes.
This project demonstrates an end-to-end ML workflow from data preprocessing to model deployment.

---

## 🚀 Live Demo

👉 https://diabetes-prediction-521.streamlit.app/

---

## 📌 Features

* Interactive medical input form
* Real-time diabetes risk prediction
* Feature scaling using trained scaler
* Clean and simple UI
* Instant prediction results

---

## 🧠 Machine Learning Model

The model was trained using patient health indicators:

* Pregnancies
* Glucose level
* Blood pressure
* Skin thickness
* Insulin level
* BMI
* Diabetes pedigree function
* Age

A **Random Forest Classifier** was trained and saved along with the scaler for deployment.

---

## 🛠️ Tech Stack

* Python
* Streamlit
* NumPy
* Scikit-learn
* Joblib

---

## 📂 Project Structure

```
diabetes-app/
│
├── diabetes_app.py        # Streamlit application
├── diabetes_model.pkl     # Trained ML model
├── scaler.pkl             # Feature scaler
├── requirements.txt       # Dependencies
└── README.md
```

---

## ⚙️ Installation (Run Locally)

1️⃣ Clone the repository

```
git clone https://github.com/YOUR-USERNAME/diabetes-app.git
cd diabetes-app
```

2️⃣ Install dependencies

```
pip install -r requirements.txt
```

3️⃣ Run the app

```
streamlit run diabetes_app.py
```

---

## 🌐 Deployment

This app can be deployed easily on **Streamlit Cloud**:

1. Push project to GitHub
2. Connect repository on Streamlit Cloud
3. Select main file and deploy

---

## 📊 How It Works

1. User enters medical details
2. Input data is scaled using trained scaler
3. Model predicts diabetes risk
4. Result is displayed instantly

---

## 🎯 Use Cases

* Healthcare analytics demonstration
* Machine Learning portfolio project
* Educational purposes
* Predictive modeling practice

---

## 📜 License

This project is for **educational and demonstration purposes only**.

---
