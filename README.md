# Airline-Regression-Model
A multiple linear regression model that predicts the number of airline delays by 15 minutes, featuring a matplotlib visualization. Regression models predicting airline delays targets the largest bottleneck in the entire airline industry, delayed flights. The data spans over 11,000 flights, primarily focusing on airports with arriving flights greater than 1000. This was purposefully chosen in order to pick a concentrated group for the most accurate findings and predictions.
# Features
- Multiple Linear Regression
- Visualization of The 3D Plane, Scatter Plots, and Surface
- Includes Source Dataset
# Requirements
- Python
- `pandas`
- `numpy`
- `sklearn(test_train_split, LinearRegression, mean_squared_error)`
- `matplotlib`
- `mplot3d`
- `math`
# Dataset
"Flight Delay Data": Kaggle. Download Here: https://www.kaggle.com/datasets/sriharshaeedala/airline-delay?resource=download
# Known Issues & Findings
As of right now, the root mean squared error is too large of an error to be deemed reliable and accurate. While it effectively uses weather delays and arriving flights to predict, there is a greater variable that contributes more to delays by 15 minutes. Arrivingflights had a significantly lesser importance in delays, which was contrary to what was originally hypothesized. With Weather delays showing greater importance, it was added as an input. 
