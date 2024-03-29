# New-York-Housing-Market_PRICE_PREDICTION
# New York Housing Dataset - Price Prediction

This project uses the New York housing dataset to perform exploratory data analysis (EDA) and predict housing prices. Various techniques, visualizations, and machine learning models have been employed to gain valuable insights and improve predictions.

## Exploratory Data Analysis (EDA)

Exploratory data analysis has been conducted using libraries such as Plotly and Seaborn. Some of the visualizations include:

- Distribution of variables
- Boxplots of price by locality.
- Charts of minimum, maximum, and mean prices by locality

## Problem and Solution

It has been identified that the total dataset exhibits dispersion in the values of the target variable (PRICE), affecting the metrics of the models.
 To address this, GridSearch, Pipelines, and additional data adjustment by locality have been used. The improved metrics by locality are as follows:

| LOCALITY        | MSE              | RMSE          | MAE          | R2           |
| --------------- | ---------------- | ------------- | ------------ | ------------ |
| New York        | 190,948,309,967.80 | 436,976.33    | 294,472.02   | 0.4366       |
| New York County | 663,382,926,500.81 | 814,483.23    | 519,056.91   | 0.5446       |
| Bronx County    | 5,375,434,664.29  | 73,317.36     | 56,334.89    | 0.5695       |
| Kings County    | 62,338,577,931.33 | 249,676.95    | 142,853.49   | 0.5483       |
| Queens County   | 11,317,306,757.92 | 106,382.83    | 73,419.79    | 0.7035       |
| Richmond County | 7,772,238,276.49  | 88,160.30     | 70,279.54    | 0.4294       |
| United States   | 838,115,089,955.41 | 915,486.26    | 631,883.97   | -0.0464      |
| Brooklyn        | 8,783,438,400.00  | 93,720.00     | 93,720.00    | NaN          |

