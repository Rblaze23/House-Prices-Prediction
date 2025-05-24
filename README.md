# House-Prices-Prediction
My work on the Kaggle Competition on House Pricing

Project Name: House Prices Prediction By Ramy Lazghab

Description: This project aims to predict house prices based on various factors like location, size, number of bedrooms, and other key features using machine learning models.

1. Dataset
The dataset includes various features such as:

Lot Area: Size of the property

Number of Bedrooms: Total bedrooms in the house

Number of Bathrooms: Total number of bathrooms

Square Footage: The total livable space

Neighborhood: The location of the house

Year Built: The construction year

Sale Price: Target variable (price of the house)

2. Data Preprocessing
Handling Missing Values: Impute missing data using median values

Feature Engineering: Creating new variables like price per square foot

Standardization: Normalizing numerical features

Encoding Categorical Variables: Converting categorical features (e.g., neighborhoods) into numerical representations

3. Model Training
The following models are tested:

Linear Regression

Random Forest

Gradient Boosting (XGBoost)

Neural Networks

4. Evaluation Metrics
Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

R² Score

5. Usage Guide
To run the prediction model, follow these steps:
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
