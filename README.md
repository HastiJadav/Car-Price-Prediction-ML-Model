# 🚗 Car Price Prediction using Machine Learning
It is a machine learning project designed to estimate car prices based on various features such as make, model, year, mileage, and more. This project leverages multiple regression models to analyze historical car price data and predict vehicle values accurately.

## 📊 Project Overview
This project implements different regression algorithms to predict car prices. The models used include:
Linear Regression
Lasso Regression
Ridge Regression
ElasticNet Regression
K-Nearest Neighbors (KNN) Regression
Support Vector Regression (SVR)
Decision Tree Regression
This model can assist car buyers, sellers, and dealerships in making informed pricing decisions based on real-world data trends.

## 📝 Dataset & Preprocessing
Missing values were handled appropriately.
Categorical variables were processed using One-Hot Encoding (OHE) and Label Encoding.
Data was split into 80% training and 20% testing.

## 📈 Model Performance
![image](https://github.com/user-attachments/assets/884b8e31-cd4e-42eb-9f68-1b0d78b53359)

## 📊 Results
KNN Regression performed the best with an R² score of 0.75.
Lasso and Ridge Regression also performed well, with R² scores around 0.72.
Linear Regression had an R² score of 0.71.
ElasticNet, SVR, and Decision Tree had relatively poor performance.

## 🔍 Conclusion
Linear, Lasso, and Ridge Regression performed well.
KNN Regression had the highest predictive power.
ElasticNet, SVR, and Decision Tree struggled to generalize.
Further hyperparameter tuning and feature engineering could improve accuracy.

## 🔮 Future Improvements
Try feature selection for better model performance.
Implement hyperparameter tuning using GridSearchCV.
Test ensemble models like Random Forest and Gradient Boosting.
Deploy the model using Flask or Streamlit.

## 👤 Author
Hasti Jadav
👨‍💻 Data Science & Machine Learning Enthusiast
📧 [hastijadav03@gmail.com]
