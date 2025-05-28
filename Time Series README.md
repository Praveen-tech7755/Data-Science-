**Time Series Inflation Rate Prediction**
This project focuses on predicting global inflation rates using time series analysis and a gradient boosting model. It leverages historical inflation data to forecast future trends.

**Key Features:**
Data Loading and Preprocessing: The project loads global_inflation_data.csv and preprocesses it by creating lagged features of the inflation rate, which are crucial for time series forecasting.
Time Series Splitting: The data is split into training and testing sets without shuffling, a standard practice for preserving the temporal order in time series data.
Inflation Rate Prediction: An XGBoost Regressor model is employed to predict future inflation rates based on the lagged values.
Model Evaluation: The performance of the prediction model is evaluated using the Mean Squared Error (MSE) metric.
**Technologies Used:**
Python
pandas for data manipulation and preparation
numpy for numerical operations
matplotlib for data visualization (though no plot output is shown in the provided snippet, it's imported)
scikit-learn for data splitting and model evaluation (e.g., mean_squared_error)
xgboost for building the regression model (XGBRegressor)
