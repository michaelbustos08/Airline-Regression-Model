# Airline-Regression-Model
A multiple linear regression model that predicts the number of airline delays by 15 minutes, featuring a matplotlib visualization. Regression models predicting airline delays targets the largest bottleneck in the entire airline industry, delayed flights. The data spans over 11,000 flights, primarily focusing on airports with arriving flights greater than 1000. This was purposefully chosen in order to pick a concentrated group for the most accurate findings and predictions.

# Findings
Multiple inputs in a linear regression model requires combining your features into one `X_train` and `X_test` table. However, this also causes to your data going from a simple 1D or 2D grid to 3D. It became evident that it was impossible to visualize a 3D plane on a 2D scatterplot, and as a result, a 3D scatter plot with 3D surface was designed and configured based upon X (`arr_flights`), Y (`weather_ct`), and Z (`lr.predict(Q)`). 

# Features
- Multiple Linear Regression
- Visualization of The 3D Plane, Scatter Plots, and Surface
- Includes Source Dataset

# Requirements
- Python
- Required Libraries:
  - `pandas`
  - `numpy`
  - `sklearn(test_train_split, LinearRegression, mean_squared_error)`
  - `matplotlib`
  - `mplot3d`
  - `math`
    
# Dataset
"Flight Delay Data": Kaggle. Download Here: https://www.kaggle.com/datasets/sriharshaeedala/airline-delay?resource=download

# Known Issues
The root mean squared error is too large of an error to be deemed reliable and accurate. While it effectively uses weather delays and arriving flights to predict, the large error indicates that there is a variable that contributes more to delays by 15 minutes. Underfitting describes this senario, as it is a common problem faced by many.
