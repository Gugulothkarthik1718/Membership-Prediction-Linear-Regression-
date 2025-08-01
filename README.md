# Membership Prediction using Linear Regression

## Project Overview

This project uses a simple linear regression model to predict the average membership duration based on the average session length. It's a fundamental machine learning project that demonstrates the process of building a predictive model, from data exploration and visualization to model training and evaluation.

## Dataset

The dataset used in this project contains two key columns:
* **Avg. Session ('S')**: The average session length.
* **Avg. Membership ('M')**: The average membership duration in months.
* link-'https://www.kaggle.com/datasets/iyadavvaibhav/ecommerce-customer-device-usage'

## Methodology

1.  **Data Loading and Exploration**: The dataset is loaded using the Pandas library, and the relationship between session length and membership duration is visualized using a scatter plot from Matplotlib.
2.  **Data Preparation**: The dataset is split into features (X - Avg. Session) and the target variable (y - Avg. Membership).
3.  **Train-Test Split**: The data is divided into training and testing sets using the `train_test_split` function from Scikit-learn to prepare for model training and validation.
4.  **Model Training**: A `LinearRegression` model from Scikit-learn is instantiated and trained on the training data.
5.  **Prediction and Evaluation**: The trained model makes predictions on the test set, and its performance is evaluated by comparing the predicted membership values against the actual values.

## How to Run

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Install the necessary Python libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```
3.  Open and run the Jupyter Notebook (`.ipynb` file) to execute the code and see the analysis and results.

## Results

The linear regression model successfully establishes a relationship between the average session length and the average membership duration. The final output includes a comparison of the actual vs. predicted values, demonstrating the model's predictive capability.
