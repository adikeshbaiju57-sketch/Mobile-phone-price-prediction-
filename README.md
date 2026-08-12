# Mobile Phone Price Prediction

## Overview
This project applies a **Linear Regression** model using Python and `scikit-learn` to predict the market prices of smartphones based on features like user ratings, storage capacity, and screen size.

## Dataset Source
* **Dataset Name:** smartphones.csv
* **Features Used:** 
  * `ratings`: Customer/user review score.
  * `storage`: Internal storage capacity (in GB).
  * `size`: Display screen size (in inches).
* **Target Variable:** `price` (Continuous numerical value)

## Methodology & Implementation
1. **Data Preprocessing:** Loaded the dataset, checked for missing values, and dropped rows with missing data.
2. **Model Training:** Split the data into training (80%) and testing (20%) sets, then trained a Linear Regression model using `scikit-learn`.
3. **Evaluation Metrics:** Evaluated performance using Root Mean Squared Error (RMSE) and R-squared ($R^2$) Score.

## Results & Performance
* **RMSE:** [Insert your printed RMSE value here]
* **R2 Score:** [Insert your printed R2 score here]

## Visualization
The actual versus predicted mobile phone prices are visualized below:

![Actual vs Predicted Prices](mobile_price_prediction.png)
