# 🚗 Vehicle Valuation System

A machine learning–powered web application that predicts the market price of a used car based on various parameters like brand, fuel type, kilometers driven, ownership, and more. Built using **React**, **Node.js**, **Python (pandas, numpy, scikit-learn, matplotlib)**, and **SQL**.

---

## 🎯 Aim

To develop a machine learning–based web application that accurately predicts the resale value of a used vehicle. The aim is to help users, car dealers, and resellers in making informed pricing decisions.

---

## 🛠️ Features

- 🚘 User-friendly form to input car details
- 📊 Predicts price using a trained ML regression model
- 🔁 ML model built with pandas, numpy, scikit-learn
- 🗃️ Stores user inputs and predictions in SQL database
- 📈 Visualizations with matplotlib (optional)
- 🌐 React-based frontend with clean UI

---

## 📂 Dataset Description

- **Source:** Kaggle / Cardekho used car data
- **Records:** ~6,000–10,000
- **Features:**
  - Car Name / Brand
  - Year of Manufacturing
  - Fuel Type
  - Transmission
  - Kilometers Driven
  - Ownership Type
  - Selling Price (Target)

---

## 🔄 Data Preprocessing

- Dropped irrelevant columns (e.g., car name string)
- Created new feature `car_age`
- One-hot encoding for fuel type, transmission, owner
- Removed outliers (extreme mileage or price)
- Train-test split (80-20)

---

## 🧠 Model Training

- Algorithms: Linear Regression, Random Forest
- Trained using scikit-learn
- Saved model using `joblib` as `model.pkl`
- Backend Python script handles prediction

---

## 📈 Evaluation Metrics

- **R² Score:** ~0.85 (good accuracy)
- **MAE:** Average absolute error
- **RMSE:** Penalizes large errors more
- Compared training vs test performance to check overfitting

---

## 💼 Real-World Applicability

- Car resellers can estimate fair prices
- Buyers can check if a car is overpriced
- Shows how ML is used in industry for predictive pricing

---

## 📝 Current Status

- ✅ Project planning complete  
- 📄 Description documented  
- 🔨 Code implementation in progress  
- 🚀 Deployment targeted soon

---

## 🧪 Technologies Used

- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Machine Learning:** Python, pandas, numpy, scikit-learn, matplotlib
- **Database:** MySQL / PostgreSQL

---

## 📝 Author

**Harshita Sinha**  
B.Tech CSE (AI/ML)  
[LinkedIn](https://www.linkedin.com/) • [GitHub](https://github.com/)

---

## 🤝 Feedback & Ideas

Open to suggestions, issues, and collabs! Feel free to open an issue or contact.

---
