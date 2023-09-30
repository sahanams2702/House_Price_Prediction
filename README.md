# House_Price_Prediction
Machine Learning
# README - Housing Price Prediction

This README provides a brief overview of the steps taken to perform housing price prediction using a linear regression model on a dataset.

## Dataset

The dataset used for this project is called "Housing.csv" and contains information about various housing properties, including features such as area, number of bedrooms, number of bathrooms, stories, and several categorical features like the presence of a mainroad, guestroom, basement, hot water heating, air conditioning, parking, prefarea, and furnishing status. The target variable is the "price" of the properties.

## Data Preprocessing

### Data Inspection
- The dataset contains 545 rows and 13 columns.
- There are no missing values in the dataset.
- The dataset does not contain any duplicate records.

### Data Encoding
- Categorical columns (e.g., "mainroad," "guestroom") are encoded using Label Encoding to convert them into numerical format.

## Splitting the Dataset
- The dataset is split into training and testing sets, with 70% of the data used for training and 30% for testing.

## Model Building - Linear Regression
- A Linear Regression model is used to predict housing prices based on the provided features.

## Model Evaluation
- Two evaluation metrics are used to assess the model's performance:
  - R-squared (R2) Score: The R2 score measures the proportion of the variance in the dependent variable that is predictable from the independent variables. A higher R2 score indicates a better fit.
  - Mean Absolute Error (MAE): MAE measures the average absolute differences between the predicted and actual values. It represents the average prediction error.

### Model Performance
- The R2 score achieved by the model is approximately 0.644, indicating that the model explains 64.4% of the variance in the housing prices.
- The Mean Absolute Error (MAE) is approximately 925,543, which represents the average prediction error in the housing prices.

This README provides a concise summary of the steps involved in the housing price prediction project using linear regression. For more details and code implementation, please refer to the code provided in the initial question.
