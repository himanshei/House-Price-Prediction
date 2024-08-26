# House-Price-Prediction

This project demonstrates the use of supervised learning and regression models to predict real estate prices based on the Boston Housing dataset. The goal is to find the best-fit model that accurately captures the overall trend in the data and provides reliable price predictions for real estate properties.

Dataset
The dataset used in this project is the Boston Housing dataset, which includes various parameters such as crime rate, number of rooms, age of property, and other factors that influence the price of real estate.

Models Used
We explored different regression models to predict housing prices:

Linear Regression:

This model attempts to find a linear relationship between the input features and the target variable (housing price).
Performance:
Mean RMSE: 5.037
Standard Deviation: 1.059
Observation: High error, indicating poor fit for this dataset.
Decision Tree:

A non-linear model that splits the data into subsets based on feature values.
Performance:
Mean RMSE: 4.185
Standard Deviation: 0.732
Observation: The model overfits the training data, resulting in zero error on the training set but poor generalization to unseen data.
Random Forest:

An ensemble model that aggregates the predictions of multiple decision trees to improve robustness and accuracy.
Performance:
Mean RMSE: 3.305
Standard Deviation: 0.686
Observation: The Random Forest model provided the best performance with the lowest error and better generalization compared to the Decision Tree model.
Methodology
Batch Learning: The models do not modify their parameters until batches of fresh data are consumed. This approach helps in efficient learning, especially with large datasets.
Cross-Validation: To avoid overfitting and ensure the model's robustness, cross-validation techniques were employed. This involves dividing the data into training and testing subsets multiple times to validate the model performance across different data splits.
Performance Measure
The primary performance metric used in this project is Root Mean Squared Error (RMSE). RMSE measures the average magnitude of the error between the predicted and actual values, with lower values indicating better model performance.
