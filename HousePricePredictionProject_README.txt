TITLE - HOUSE PRICE PREDICTION PROJECT

Description of the project:
This project is designed to provide a prediction of housing prices that are based on important information such as square footage of the house, the location of the house, and the type of property that the house is located in.
My project is on building a model that predicts housing prices from user input relies on machine learning techniques.

Dataset used: House Price Prediction Dataset.csv
Dataset Source: Kaggle
Link - https://www.kaggle.com/datasets/zafarali27/house-price-prediction-dataset?resource=download

Description of dataset:
The dataset contains information about multiple houses with features including:
Area (square footage)
Number of bedrooms and bathrooms
Number of floors
Age of the house
Location (Urban, Suburban, Rural)
Condition (Poor, Fair, Good, Excellent)
Garage availability (Yes/No)
Price (target variable)

Steps Performed
Data Cleaning
Removed unnecessary columns (e.g., ID)
Checked for missing values
Ensured correct data types

2.Exploratory Data Analysis (EDA)
Analyzed relationships between features and price
Identified key influencing factors such as area and location

3. Visualization
Used plots to understand feature distributions
Compared price variations across different categories

4. Model Building
Applied Linear Regression model
Encoded categorical variables using One-Hot Encoding
Split dataset into training and testing sets
Trained the model using Scikit-learn

Results: 
The model successfully predicts house prices based on input features

1. Evaluation Metrics:
Mean Squared Error (MSE): ~2.45e+10
Root Mean Squared Error (RMSE): ~156,50
Mean Absolute Error (MAE): ~124,300

2. Key Findings:
Area is the most significant factor influencing price
Location and condition also strongly impact pricing
Linear regression provides a good baseline model

Tools Used:
Python Programming
Python Libraries: - NumPy
                  - Pandas
                  - Matplotlib
                  - Scikit-learn

Conclusion:
My project uses machine learning with Python to predict home price based on numerous attributes are exemplified here. Although linear regression is a decent foundation from which machine learning starts its predictions, machine learning’s more sophisticated models (such as random forest and gradient boosting) can yield better results than linear regression. In addition, this project also demonstrates the significant role that data preprocessing and feature engineering play through creating predictive models.

Author Name: Suyodhannan. S. Nair
Golden Gate University Worldwide
Summer-C Batch, Computing



