# House Price Prediction

## OIBSIP – Data Analytics Project 2

This project focuses on predicting house sale prices using machine learning techniques. The project uses the House Prices dataset and applies data analysis, visualization, feature selection, and Linear Regression to predict `SalePrice`.

## Project Objective

The objective of this project is to build a machine learning model that can predict house sale prices using important features of residential properties.

## Dataset

The dataset contains information about residential properties along with their actual sale prices.

The original dataset contains **1,460 records and 81 columns**.

## Features Used

The following eight features were selected for the prediction model:

* `OverallQual` – Overall quality of the house
* `GrLivArea` – Above-ground living area
* `GarageCars` – Garage capacity
* `TotalBsmtSF` – Total basement area
* `1stFlrSF` – First-floor area
* `YearBuilt` – Year the house was built
* `FullBath` – Number of full bathrooms
* `TotRmsAbvGrd` – Total rooms above ground

### Target Variable

* `SalePrice` – Actual house sale price

## Project Workflow

1. Load the dataset
2. Understand the dataset
3. Check statistical information
4. Check and handle missing values
5. Perform data cleaning
6. Analyze the distribution of house sale prices
7. Perform correlation analysis
8. Analyze important features
9. Select features for the model
10. Split the dataset into training and testing sets
11. Train a Linear Regression model
12. Generate house price predictions
13. Evaluate model performance
14. Visualize actual vs predicted prices
15. Perform residual analysis

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Model

### Linear Regression

Linear Regression was used to predict `SalePrice` based on the eight selected house features.

## Model Performance

The model achieved the following results on the test dataset:

| Metric   |           Result |
| -------- | ---------------: |
| MAE      |        25,123.51 |
| MSE      | 1,568,831,973.14 |
| RMSE     |        39,608.48 |
| R² Score |           0.7955 |

## Results

The model achieved an **R² score of 0.7955**, indicating that the selected features explain approximately **79.55% of the variation in house sale prices on the test dataset**.

The actual vs predicted visualization and residual analysis were used to evaluate the model's prediction behavior.

## Project Structure

```text
DataAnalytics-L2-HousePricePrediction/
│
├── House_Price_Prediction.ipynb
├── house_prices_cleaned.csv
└── README.md
```

## Conclusion

A Linear Regression model was successfully developed to predict house sale prices using selected property features. The project demonstrates the complete workflow from data preparation and exploratory analysis to machine learning model training and evaluation.

This project was completed as part of the **OIBSIP Data Analytics Internship – Project 2**.

