# Housing Price Prediction

## Overview
This project involves predicting housing prices using a linear regression model. The data is preprocessed, cleaned, and then used to train and test the model.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Data Preprocessing
- Loading the data and displaying sample rows.
- Checking the shape and information of the dataset.
- Checking for and handling missing values.
- Removing outliers from the target variable (median_house_value).
- Applying a log transformation to the target variable to make it more normally distributed.
- Splitting the data into training and testing sets.
- Visualizing the distributions of the features.
- Creating dummy variables for categorical features.
- Generating new features such as bedroom_per_room and population_per_household.

## Model Training and Evaluation
- Defining the feature matrix x and the target vector y.
- Splitting the data into training and testing sets.
- Applying preprocessing steps to the training and testing data.
- Training a linear regression model on the training data.
- Making predictions on the testing data.
- Evaluating the model using the R² score and the Root Mean Squared Error (RMSE).

## Results
The model's performance is evaluated using the R² score and RMSE.
- R² Score: 0.67
- RMSE: 0.298

## Acknowledgments
- The dataset used in this project is provided by California Housing Prices.
- NeuralNine (YouTube Channel)
- Greg Hogg (YouTube Channel)
