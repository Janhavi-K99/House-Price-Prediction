# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting house prices using Machine Learning techniques based on various property characteristics such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

The objective of this project is to analyze housing data, identify the key factors that influence property prices, and develop predictive models capable of estimating house prices with reasonable accuracy.

The project demonstrates a complete Machine Learning workflow including data exploration, preprocessing, feature engineering, model development, evaluation, and visualization.

## Objectives

* Understand and analyze the housing dataset.
* Perform data cleaning and preprocessing.
* Transform categorical variables into machine-readable format using One-Hot Encoding.
* Develop regression models for house price prediction.
* Compare the performance of multiple Machine Learning algorithms.
* Visualize important patterns and relationships within the dataset.
* Generate meaningful insights from the analysis.

## Dataset Description

The dataset contains information about residential properties along with their corresponding selling prices.

The features available in the dataset include:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking Spaces
* Main Road Access
* Guest Room Availability
* Basement Availability
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

The target variable for prediction is:

* House Price

## Data Preprocessing

Several preprocessing steps were performed before model development.

The dataset was examined for missing values and duplicate records to ensure data quality. Categorical attributes such as furnishing status and yes/no features were converted into numerical format using One-Hot Encoding. This transformation allowed the Machine Learning algorithms to process categorical information effectively.

Feature relationships were further explored through correlation analysis and visualizations to understand their influence on house prices.

## Model Development

The dataset was divided into training and testing sets using an 80:20 split ratio.

Two Machine Learning models were developed and evaluated:

### Linear Regression

Linear Regression was used as the baseline model to establish relationships between housing features and house prices.

### Random Forest Regression

Random Forest Regression was implemented to capture more complex patterns in the data and to analyze feature importance.

## Model Evaluation

The models were evaluated using the following performance metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The Linear Regression model achieved the best overall performance with an R² score of approximately 0.65, indicating that the model explains around 65% of the variation in house prices within the dataset.

The Random Forest model was also evaluated and compared, but Linear Regression provided better results for this particular dataset.

## Data Visualization

Several visualizations were created to support data analysis and model interpretation.

The project includes:

* Correlation Heatmap
* Area vs Price Scatter Plot
* Average Price by Bedrooms
* Feature Importance Analysis
* Actual vs Predicted Price Comparison
* House Price Distribution Histogram

These visualizations helped identify important features, understand pricing trends, and evaluate model performance.

## Key Findings

The analysis revealed that area is the most influential factor affecting house prices. Other important contributors include bathrooms, parking facilities, air conditioning, and the number of stories.

The majority of properties belong to the middle-price segment, while a smaller number of premium properties create a right-skewed distribution of house prices.

Feature importance analysis further confirmed that structural characteristics of a property contribute more significantly to house value than several optional amenities.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Structure

House-Price-Prediction/

├── analysis.ipynb

├── Housing.csv

├── README.md

└── PLOTS/

## Future Scope

Future improvements may include incorporating location-based features, property age, nearby facilities, and market trends. Advanced machine learning techniques such as Gradient Boosting, XGBoost, and Hyperparameter Tuning can also be explored to further improve predictive performance.

## Author

Janhavi Kolamkar

B.E. Electronics and Telecommunication Engineering

Pune Institute of Computer Technology (PICT)
