# 🚗 Car Price Predictor

A clean, practical, and end-to-end **Machine Learning + Web App** project that predicts the **resale price of a car** based on real-world features. This project combines **data analysis, model building, and web deployment** into one smooth experience.

---

## 🔍 Project Overview

Buying or selling a used car often involves guesswork. This project aims to remove that uncertainty by predicting a car’s price using historical data and machine learning.

The application takes the following inputs:

* 🚘 **Car Brand**
* 🧾 **Car Model**
* ⛽ **Fuel Type**
* 📅 **Year of Purchase**
* 🛣️ **Kilometers Driven**

…and instantly returns a **predicted resale price**.

The model is trained using **Linear Regression** with **hyperparameter tuning**, achieving around **90% accuracy**.

---

## 🧠 Machine Learning Workflow

* Data cleaning & preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection & encoding
* Model training using **Linear Regression**
* Hyperparameter tuning for better performance
* Model serialization using `pickle`

---

## 🌐 Web Application

The ML model is deployed using **Flask** and presented through a **two-page interactive website** built with:

* **HTML & CSS** for UI
* **Flask** for backend integration

### Pages:

* **Home Page** – Introduction and navigation
* **Prediction Page** – Input car details and get instant price prediction

---

## 🛠️ Tech Stack

* **Python**
* **Flask**
* **HTML / CSS**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **Gunicorn** (for deployment)

---

## 📁 Project Structure

```
car/
├── app.py
├── templates/
│   ├── index.html
│   └── predictor.html
├── static/
│   ├── styles.css
│   └── assets/
├── LinearRegressionModel.pkl
├── Cleaned_Car_data.csv
├── requirements.txt
├── README.md
```

---

## 📊 Model Performance

* Algorithm: **Linear Regression**
* Accuracy: **~90%**
* Optimized using hyperparameter tuning

