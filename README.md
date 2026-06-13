# Capacity Planning Using SARIMAX and Conformal Prediction

This repository contains the code and sample data used to demonstrate a capacity planning framework based on SARIMAX forecasting enhanced with Conformal Prediction intervals.

The approach is illustrated using a life insurance operational dataset and shows how calibrated prediction intervals can support infrastructure and storage capacity planning decisions by quantifying forecast uncertainty.

### Objectives
Forecast future storage growth using SARIMAX.
Incorporate business events and known purge activities.
Generate calibrated prediction intervals using Conformal Prediction.
Estimate threshold crossing dates for capacity planning.
Provide decision support through uncertainty-aware forecasts.

### Methodology
Data preparation and cleansing.
Time-series feature engineering.
SARIMAX model development.
Forecast generation.
Conformal Prediction calibration.
Threshold crossing analysis.
Capacity planning recommendations.
Technologies Used
Python
Pandas
NumPy
Statsmodels
MAPIE
Matplotlib
Google Colab

### Reproducing the Results
Clone the repository.
Open the notebook in Google Colab or Jupyter Notebook.
Update the dataset path if required.
Execute the notebook cells sequentially.
Review the generated forecasts and conformal prediction intervals.

### Sample Data

The repository contains a sanitized sample dataset created for demonstration purposes. No production or customer data is included.

### Disclaimer

This project is intended for research and educational purposes. Results may vary depending on data characteristics, forecast horizon, and model assumptions.

### Author

Sriram Anjanadri
