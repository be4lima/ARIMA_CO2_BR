# CO2 Emission Prediction in Brazil using ARIMA
- **Objective**: Develop an ARIMA model to forecast CO2 emissions in Brazil using historical data and analyze the model's performance in predicting future values.
- **Data Source**: Historical CO2 emissions data for Brazil available through OWID.
- **Data Preprocessing**:
  - Data inspection, handling missing values, and outlier treatment.
  - Time series decomposition to analyze seasonal, trend, and noise components.
  - Stationarity tests (Augmented Dickey-Fuller) and differencing the series to achieve stationarity.
- **Modeling**:
  - Application of the ARIMA (AutoRegressive Integrated Moving Average) model.
  - Use of the `auto_arima` function to identify the optimal parameters (p, d, q).
  - Model fitting to historical data and residual analysis.
- **Validation and Evaluation**:
  - Splitting data into training and testing sets to evaluate the model's predictive power.
  - Evaluation metrics used: Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE).
  - Assessment of model adequacy through residual analysis.
- **Conclusion**:
  - Discussion of the results obtained and the suitability of the ARIMA model for forecasting CO2 emissions in Brazil.
  - Suggestions for future improvements, such as including exogenous variables or using other time series models.

