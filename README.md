# T-20-Score-Prediction

# T20 Score Prediction using Linear Regression and Sequential Feature Selection

This project aims to predict the final score of a T20 cricket match using linear regression and sequential feature selection. It utilizes historical match data to train a model that can estimate the total runs scored in an innings.

## Project Overview

T20 cricket is a high-scoring and fast-paced format. Predicting the final score during a match can be challenging, but with the help of machine learning, we can build models that provide reasonable estimates. This project explores the use of linear regression, a simple yet effective algorithm, combined with sequential feature selection to identify the most relevant features for prediction.

## Dataset

The project uses a dataset of T20 cricket matches containing various features such as:

*   **Overs:** The number of overs bowled so far.
*   **Runs:** The current total runs scored.
*   **Wickets:** The number of wickets fallen.

## Methodology

1.  **Data Preprocessing:** The dataset is cleaned and preprocessed. This may include handling missing values, converting categorical variables (like team names) into numerical representations (e.g., one-hot encoding), and feature scaling.
2.  **Sequential Feature Selection:** This technique is used to select the most relevant features for the linear regression model. It can be either forward selection (starting with no features and adding them one by one) or backward elimination (starting with all features and removing them one by one).
3.  **Linear Regression Model:** A linear regression model is trained on the selected features to predict the final score.
4.  **Model Evaluation:** The model's performance is evaluated using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

## Libraries Used

*   Python
*   Pandas
*   NumPy
*   Scikit-learn
