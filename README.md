# Forecasting-U.S.-Housing-Prices-Using-Machine-Learning-Models
Forecasting U.S. Housing Prices Using Machine Learning Models
This notebook focuses on analyzing and predicting U.S. housing prices using various economic and demographic indicators. The dataset includes the Case-Shiller Home Price Index along with features such as GDP per capita, CPI, unemployment rate, median income, and more.

## Data Preprocessing
Loaded and indexed the dataset by the DATE column

Removed columns with low correlation and multicollinearity based on Pearson correlation analysis

## Feature Analysis
Visualized the relationship between each feature and the target variable using scatter plots

Performed time series decomposition to observe trend, seasonal, and residual components

## Model Training and Evaluation
Scaled input features using StandardScaler

Trained and evaluated multiple regression models including:

Linear Regression

ElasticNet

Random Forest

Gradient Boosting

Support Vector Regressor (SVR)

XGBoost Regressor

## Results
Random Forest Regressor achieved the best performance with an MSE of 1.67 and an R² Score of 0.999

A comparative heatmap was used to summarize the performance of all models clearly
