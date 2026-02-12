🏥 Medical Insurance Cost Prediction using Machine Learning
📖 Project Overview

This project builds a Machine Learning model to predict medical insurance charges based on demographic and lifestyle factors such as age, BMI, smoking status, number of children, and region.

The project includes Exploratory Data Analysis (EDA), data preprocessing, regression modeling, model comparison, and visualization.

🎯 Problem Statement

To develop a predictive model that estimates medical insurance costs using supervised machine learning techniques.

📊 Dataset Features

Age – Age of the individual

Sex – Gender (Male/Female)

BMI – Body Mass Index

Children – Number of dependents

Smoker – Smoking status

Region – Residential area

Charges – Medical insurance cost (Target Variable)

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔍 Exploratory Data Analysis

Distribution analysis of age and BMI

Correlation heatmap

Feature importance visualization

Actual vs Predicted comparison plots

🤖 Models Implemented

Linear Regression

Random Forest Regressor

📈 Model Performance
Model	R² Score
Linear Regression	0.74
Random Forest	0.83

The Random Forest model outperformed Linear Regression, indicating non-linear relationships between features and insurance charges.

📊 Key Insights

Smoking status has the highest impact on insurance charges.

BMI and Age significantly influence medical costs.

Random Forest captures complex patterns better than Linear Regression.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/Medical-Insurance-Cost-Prediction-ML.git


Install dependencies:

pip install -r requirements.txt


Run the notebook:

Medical_Insurance_Cost_Prediction.ipynb

📌 Conclusion

This project demonstrates how machine learning can be applied to predict healthcare costs effectively. The comparative analysis highlights the importance of selecting appropriate models for regression tasks.
