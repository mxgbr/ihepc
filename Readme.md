Time Series Forecasting for Residential Energy Load Prediction with ARIMA and SVR

Author: Max Gaber

This project applies the ARIMA and SVR model to the UCI IHEPC dataset.
Please find further information in the attached paper.

Meaning of the different notebooks:
1. test_data.ipynb creates test data in form of a sine curve with noise
2. preprocessing.ipynb cleans and pre-processes the UCI IHEPC dataset and saves it as a pickle file
3. exploration.ipynb performs statistical analyses on the data
4. arima.ipynb performs ARIMA forecast
5. svr.ipynb performs SVR forecast

The IHEPC dataset is available at https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption