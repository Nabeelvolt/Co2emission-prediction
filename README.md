# Co2emission-prediction
This complete 2021 CO2 and Greenhouse Gas Emissions dataset is a collection of key metrics maintained by Our World in Data. It is updated regularly and includes data on CO2 emissions (annual, per capita, cumulative and consumption-based), other greenhouse gases, energy mix, and other relevant metrics.

Import necessary libraries and modules for data manipulation, visualization, and model building.
Load the dataset from a CSV file into a pandas DataFrame.
Remove rows with missing values in the 'co2' column to clean the data.
Select relevant features for CO2 emissions prediction, including 'year', 'population', 'gdp', and others.
Handle missing values in the dataset using a mean imputer to fill the NaN values with the mean of each feature.
Split the data into training and testing sets for model evaluation.
Perform hyperparameter tuning using GridSearchCV to find the best hyperparameters for a RandomForestRegressor model.
Calculate evaluation metrics (MAE, MSE, and R2) on the test set to assess the model's performance.
Predict future CO2 emissions for the next 'n' years using the trained model.
Create a custom x-axis with desired year intervals for visualization.
Plot the historical CO2 emissions data along with the future CO2 emission predictions on the customized x-axis.
The goal is to build a model that predicts future CO2 emissions based on historical data and relevant features. The code handles missing values, optimizes model hyperparameters, and visualizes the predictions with a custom x-axis showing the desired year intervals.
