
## House Price Prediction Project

## Overview

This repository contains the implementation of a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms. The project explores essential concepts in data analysis, machine learning, and model evaluation.

## Dataset

The dataset used for this project is provided in the file **'kc_house_data.csv'**. It includes various features related to houses, such as square footage, number of bedrooms, bathrooms, and more. The dataset is crucial for training and evaluating the predictive model.

**Dataset Link:** https://www.kaggle.com/datasets/shivachandel/kc-house-data/code

## Project Tasks

1. **Data Loading and Exploration:**
   - Loaded the dataset into a pandas frame.
   - Explored the features and gained insights into the data.

2. **Feature Selection and Preparation:**
   - Selected relevant features: square footage, number of bedrooms, and number of bathrooms.
   - Split the data into training and testing sets for model training.

3. **Model Development and Evaluation:**
   - Implemented a linear regression model using scikit-learn.
   - Evaluated the model using metrics like R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
   - Explored visualization techniques to understand feature relationships.

4. **Model Coefficients and Interpretation:**
   - Analyzed model coefficients and intercept, providing insights into feature influence.

5. **Predictions on New Data:**
   - Demonstrated model predictions on new data, showcasing its application in real-world scenarios.

## Project Outcome

- **R-squared (R²) Score:** 0.509
- **Mean Absolute Error (MAE):** \$174,662.93
- **Root Mean Squared Error (RMSE):** \$272,465.84

The linear regression model exhibited a moderate performance, explaining 50.9% of the variance in house prices. The analysis provides valuable insights for understanding housing market dynamics and serves as a foundation for future enhancements and feature explorations.

## Technologies Used

- **Python:** Programming language used for data analysis and model implementation.
- **Pandas:** Data manipulation and analysis library in Python.
- **Scikit-Learn:** Machine learning library for building and evaluating predictive models.
- **Matplotlib and Seaborn:** Libraries for data visualization.
- **Google Colab:** Cloud-based platform for running Python code and Jupyter notebooks.


