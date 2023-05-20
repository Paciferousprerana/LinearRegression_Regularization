# LinearRegression with Regularization

## Problem Statement

Predict the bike-sharing counts per hour based on the features including weather, day, time, humidity, wind speed, season e.t.c.

(Linear regression with regularization is a popular technique used for predicting continuous variables, and it helps prevent overfitting by adding a penalty term to the model.)

## Objectives

* perform data exploration and visualization
* implement linear regression using sklearn and optimization
* apply regularization on regression using Lasso, Ridge and Elasticnet techniques
* calculate and compare the MSE value of each regression technique
* analyze the features that are best contributing to the target

### Dataset

The dataset chosen for this project is [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset).  This dataset contains the hourly and daily count of rental bikes between the years 2011 and 2012 in the capital bike share system with the corresponding weather and seasonal information. This dataset consists of 17389 instances of 16 features. 

### Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in Jupyter Notebook or Google Colab.

3. Download the dataset using the link provided in the notebook.

### Usage
1.Open the ipynb file.

2. Load the bike-sharing dataset into the notebook.

3. Preprocess the dataset by performing data cleaning, handling missing values, scaling features, encoding categorical variables, and splitting the data into training and testing sets.

4. Implement the linear regression model with regularization using scikit-learn's linear_model module. Experiment with different regularization technique (e.g., Lasso regularization, Ridge regularization).

5. Train the linear regression model using the training data and evaluate its performance using suitable evaluation metrics (e.g., mean squared error, R-squared).

6. Adjust the hyperparameters of the model (e.g., regularization strength, learning rate) if necessary to improve performance.

7. Make predictions on the test data using the trained model and assess the accuracy of the predictions.

### Troubleshooting
* Ensure that the dataset file is correctly specified and placed in the same directory as the ipynb Notebook.

* Check for any missing libraries or dependencies and install them using the pip install command if necessary.
