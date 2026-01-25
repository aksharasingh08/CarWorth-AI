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

## 🚀 How to Run Locally

1. Clone the repository

```bash
git clone <repo-url>
cd car
```

2. Create a virtual environment & install dependencies

```bash
pip install -r requirements.txt
```

3. Run the Flask app

```bash
python app.py
```

4. Open browser and visit:

```
http://127.0.0.1:5000/
```

---

## 📊 Model Performance

* Algorithm: **Linear Regression**
* Accuracy: **~90%**
* Optimized using hyperparameter tuning

---

## ✨ Key Highlights

* End-to-end ML project (EDA → Model → Deployment)
* Clean and beginner-friendly codebase
* Real-world use case
* Interactive web interface
* Resume-ready project

---

## 📌 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Add brand-wise performance comparison
* Improve UI with JavaScript
* Deploy on cloud with database support

---

## 🙌 Acknowledgement

This project was built as a hands-on learning experience to strengthen skills in **Machine Learning, Flask, and deployment workflows**.

---

⭐ If you like this project, feel free to star the repo and share feedback!
