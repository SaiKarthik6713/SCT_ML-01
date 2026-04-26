📌 Project Overview

This project aims to build a Linear Regression model to predict house prices based on important features such as square footage, number of bedrooms, and number of bathrooms.

The model helps in estimating property prices, which can be useful for buyers, sellers, and real estate businesses.

📊 Dataset Description

The dataset contains details about houses and their corresponding prices.

Features:
SquareFeet: Area of the house in square feet
Bedrooms: Number of bedrooms
Bathrooms: Number of bathrooms
Price: Target variable (house price)
📁 Sample Dataset
SquareFeet,Bedrooms,Bathrooms,Price
800,2,1,120000
1000,2,2,150000
1200,3,2,200000
1500,3,3,250000
1800,4,3,320000
2000,4,4,400000
2200,5,4,450000
2500,5,5,500000
2700,4,4,520000
3000,5,5,600000
🎯 Objective

The main objective of this project is to:

Predict house prices based on input features
Understand the relationship between house size and price
Build a simple and interpretable machine learning model
⚙️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
🧠 Methodology
Load and explore the dataset
Select features (SquareFeet, Bedrooms, Bathrooms)
Split data into training and testing sets
Train a Linear Regression model
Evaluate the model using regression metrics
Predict prices for new data
📈 Model Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
🧮 Model Formula

The Linear Regression model follows:

Price = w1 * SquareFeet + w2 * Bedrooms + w3 * Bathrooms + b

Where:

w1, w2, w3 are coefficients
b is the intercept
🚀 Expected Output

The model predicts house prices based on input values.

Example:

Input → (1500 sq ft, 3 bedrooms, 2 bathrooms)
Output → Estimated price
📌 Conclusion

Linear Regression provides a simple yet effective way to predict house prices. It helps in understanding how different factors influence pricing.
