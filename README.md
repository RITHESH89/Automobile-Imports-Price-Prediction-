# Automobile Price Prediction

This project predicts car prices using machine learning techniques.The Automobile Imports Price Prediction project aims to predict the price of imported cars using machine learning techniques. The dataset contains various automobile characteristics such as insurance risk rating, engine specifications, mileage, and other price-related indicators.

By analyzing these features, a supervised regression model is trained to accurately estimate the price of automobiles.

## Objective
- To build a machine learning regression model that predicts automobile prices      based on multiple technical and risk-related features.

## Dataset Description
 The dataset includes the following types of features:
- Insurance Risk Rating (symboling)
- Car Brand and Body Type
- Fuel Type and Aspiration
- Engine Specifications (engine size, horsepower)
- Mileage (city MPG, highway MPG)
- Vehicle Dimensions and Weight
- Target Variable: price
- Each row represents one automobile with its corresponding attributes.

## Machine Learning Approach

- Problem Type: Supervised Learning
- Task: Regression
- Algorithm Used: Random Forest Regressor

- Random Forest was chosen due to its ability to handle non-linear relationships and provide high accuracy.

## Algorithms Used
- Linear Regression
- Random Forest Regression

## Tools
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
- Data Loading
- Data Cleaning & Handling Missing Values
- Encoding Categorical Variables
- Feature Selection
- Train-Test Split
- Model Training
- Model Evaluation
- Price Prediction
- Visualization of Results

 ## Automobile-Price-Prediction/
│
├── data/
│   └── Automobile.csv
│
├── notebook/
│   └── Automobile_Price_Prediction.ipynb
│
├── README.md
└── requirements.txt


## Model Evaluation
- The model performance is evaluated using:
- R² Score
- Mean Absolute Error (MAE)
-A visualization comparing Actual Price vs Predicted Price is also included.

 ## Result
“The Random Forest regression model accurately predicted automobile prices with strong performance, achieving a high R² score and low prediction error.”
