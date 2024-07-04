# Currency Exchange Rate Prediction Project

This project involves building a predictive model for currency exchange rates using a dataset from the Federal Reserve.

## Steps

### 1. Importing Packages
Load essential libraries for data manipulation, visualization, and modeling.

### 2. Data Importation
Import the dataset from the Federal Reserve for analysis.

### 3. Data Inspection and Wrangling
- Inspect the data by displaying the first few rows and checking the dataset's structure.
- Convert the `Time_Series` column to a datetime format and set it as the index.

### 4. Exploratory Data Analysis (EDA)
- Plot the time series data to visualize the exchange rates over time.
- Calculate and plot the rolling average to observe trends over months.
- Analyze the distribution of currency rates using box plots.

### 5. Autoregressive Modeling
- Resample the data to a weekly frequency.
- Analyze the autocorrelation and partial autocorrelation functions (ACF and PACF) to understand the data's time dependencies.

### 6. Model Building
- Split the data into training and testing sets.
- Build and fit an Autoregressive (AR) model to the training data.
- Evaluate the model's performance using Mean Absolute Error (MAE) for both baseline and AR predictions.
- Perform walk-forward validation to test the model's predictive power on unseen data.
- Visualize the predictions against the actual test values to assess the model's accuracy.
