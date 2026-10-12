# # Toyota Corolla Price Prediction Model
Automated multilinear regression model to predict used car prices based on vehicle specifications like mileage, age, HP, and weight.

## 1. Business Problem
* **1.1 Business Objective**: Help an online car sales platform improve user experience and automate car valuation by predicting the price of a vehicle based on key specifications
* **1.2 Features Used**: `price`, `age_08_04`, `KM`, `HP`, `cc`, `Doors`, `Gears`, `Quarterly_Tax`, and `Weight`

## 2. Data Pre-processing & Outlier Treatment
* Handled data cleaning and verified data types.
* Detected and treated influential data points and outliers using Cook's distance and influence plots.

## 3. Model Building & Diagnostics
* Performed multilinear regression with `price` as the output/target variable
* Evaluated multicollinearity using **VIF** and regression diagnostics (**AvPlots**, **Influence Index Plots**).
* Documented comparative **RMSE** and **R-Squared** values for training and testing datasets.

## 4. Business Impact
* Empowers buyers and sellers with instant, reliable price estimations, improving platform engagement and transaction transparency
