# 🏥 Medical Insurance Cost Prediction using Machine Learning

> An end-to-end regression-based machine learning project for predicting healthcare insurance charges using demographic and lifestyle data.

**Author:** Vijay Lalit  
**Technologies:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn  


## 📖 Project Overview
This project builds a Machine Learning model to predict medical insurance charges based on demographic and lifestyle factors such as age, BMI, smoking status, number of children, and region.

The project includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Regression Modeling
- Model Comparison
- Performance Visualization

---

## 🎯 Problem Statement
To develop a predictive model that estimates medical insurance costs using supervised machine learning techniques.

---

## 📊 Dataset Features

- **Age** – Age of the individual  
- **Sex** – Gender (Male/Female)  
- **BMI** – Body Mass Index  
- **Children** – Number of dependents  
- **Smoker** – Smoking status  
- **Region** – Residential area  
- **Charges** – Medical insurance cost (Target Variable)

---

## 🤖 Models Implemented

1. Linear Regression  
2. Random Forest Regressor  

---

## 📈 Model Performance

| Model | R² Score |
|-------|----------|
| Linear Regression | 0.744 |
| Random Forest | 0.835 |

The Random Forest model outperformed Linear Regression, indicating the presence of non-linear relationships in the dataset.

---

## 📊 Key Insights

- Smoking status has the highest impact on insurance charges.
- BMI and Age significantly influence medical costs.
- Random Forest captures complex patterns better than Linear Regression.

---

## 🚀 How to Run

1. Clone the repository:
git clone https://github.com/vijaylalit-PA/Medical-Insurance-Cost-Prediction-ML.git

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
Medical_Insurance_Cost_Prediction.ipynb


---

## 📌 Conclusion
This project demonstrates how machine learning techniques can effectively predict healthcare insurance costs and highlights the importance of model comparison in regression tasks.
