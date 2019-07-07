# time-series-forecasting-methods
This repo compares boosting method performance when forecasting hourly energy consumption. In addition to being compared to each other, the boosting methods are compared to an ARIMA model as a baseline.

### Methods considered include:
* XGBoost
* LightGBM
* Random Forest Regression
* ARIMA

### Goals:

* Demonstrate the predictive value of lagged factors.
* Identify a method of optimally, algorithmically generating lagged factors.
* Identify differences between methods:
  * Determine most accurate method.
  * Describe why one method is more robust to another.
  * Describe penalty terms and their purpose.
  * Compare generalizability of different methods.
    * Skedasticity
    * Autocorrelation of residuals
    * Perfomance of Nested Validation
  * Demonstrate pros/cons of methods.
