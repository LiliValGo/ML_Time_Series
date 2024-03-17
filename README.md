# Colombia Crop Yield Prediction

This project uses time series data to predict corn crop yield in Colombia.

## Data

The training data was obtained from [Datos Abiertos Colombia](https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/RENDIMIENTO-DE-CULTIVOS-EN-COLOMBIA-POR-A-O/fgh5-rjkd). All data related to corn crops were selected.

## Methodology

* Data processing and visualization were performed with Pandas and Seaborn.

* Two-time series linear regression models were constructed using two data transformation processes:

  - Time-Step Feature
  - Lag Feature

## Metrics

The models were evaluated using the following metrics:

* R-squared
* Mean Squared Error (MSE) and Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* Residual Analysis

  - A visual analysis of the residuals was carried out using Matplotlib and Seaborn.

  - A quantitative analysis of the residuals was conducted using the Shapiro-Wilk normality test.

## Conclusions

It was concluded that using either transformation technique for the model's input features (Time-Step Feature and Lag Feature) does not represent much variation in the model's results except for the p-value of the Shapiro-Wilk normality test which marked a slight difference.

