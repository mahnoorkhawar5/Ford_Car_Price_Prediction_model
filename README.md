# 🚗 Ford Car Price Prediction

This project is a **Machine Learning-based price prediction system** for Ford cars.  
It uses car features such as **model, transmission type, fuel type, mileage, year, and engine size** to predict car prices.

The project is implemented in **Python** using **Scikit-learn** and follows standard ML preprocessing and modeling steps.

---

## 📌 Project Overview

Machine learning models cannot understand text data directly.  
In this project, categorical features like car model and fuel type are converted into numerical form using **Label Encoding**, making the dataset suitable for training ML models.

The final model predicts the **estimated price of a Ford car** based on input features.

---

## 📂 Dataset Features

The dataset includes the following attributes:

- `model` – Car model (Fiesta, Focus, etc.)
- `year` – Manufacturing year
- `transmission` – Manual / Automatic / Semi-Auto
- `fuelType` – Petrol / Diesel / Hybrid
- `mileage` – Distance driven
- `engineSize` – Engine size
- `price` – Target variable (car price)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Data Preprocessing

- Handled missing values
- Converted categorical features into numerical format using **LabelEncoder**
- Created a safe copy of the dataset to avoid altering original data
- Stored encoders for future inverse transformations

Example encoded columns:
- `model`
- `transmission`
- `fuelType`

---

## 🤖 Machine Learning Workflow

1. Data loading
2. Data cleaning & preprocessing
3. Label encoding of categorical features
4. Train-test split
5. Model training
6. Model evaluation
7. Price prediction

---

## 🎯 Objective

The main objective of this project is to:
- Learn **data preprocessing techniques**
- Understand **categorical encoding**
- Build a **regression-based ML model**
- Predict car prices accurately
- Create a **portfolio-ready ML project**

---

## 📊 Use Cases

- Used car price estimation
- Beginner ML practice project
- Data preprocessing & feature engineering learning
- Academic or portfolio submission

---

## 🚀 Future Improvements

- Use One-Hot Encoding where appropriate
- Try advanced models like Random Forest or XGBoost
- Hyperparameter tuning
- Build a web app using Flask or Streamlit

---

## 📁 File Structure

