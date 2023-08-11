# Prediction-Of-Product-Sales

## Analyzing the product sales of store outlets and predicting future outcomes.

Charlie Ventura

## Data Dictionary

<p align = "center"> 
  <img src="Screenshot 2023-07-13 at 7.54.49 PM.png">
</p>

## Histogram of Item Outlet Sales

<p align = "center"> 
  <img src="Screenshot 2023-07-13 at 9.02.49 PM.png">
</p>

- The Histogram is left skewed indicating that there are more item sales on the lower end

## Heatmap 

<p align = "center"> 
  <img src="Screenshot 2023-07-13 at 9.08.53 PM.png">
</p>

- There is a moderate correlation between Item MRP and Item Outlet Sales

 ### Machine Learning Using the Following Models:
    - Linear Regression Model
    - Random Forest Regressor Model
    - Tuned Random Forest Regressor Model

## Models Evaluated & Results

- Linear Regression Model (Testing Set):
  - R^2: 0.5671
  - MAE: 804.1046
  - RMSE: 1092.8554

- Random Forest Regressor Model (Testing Set):
  - R^2: 0.5598
  - MAE: 766.3192
  - RMSE: 1102.1033

- Tuned Random Forest Regressor Model (Testing Set):
  - R^2: 0.5944
  - MAE: 734.6482
  - RMSE: 1057.819


- The Final Model Chosen was a `Random Forest Regressor Model.`
- For the testing set on the model, `59.4%` of the variance in y was explained by x. 
- The Mean Absolute Error was off by about `$734.65`.
- The Root Mean Squared Error had a calculation of `$1057.82`.

The model in its current state would not provide reliable predictions. The MAE and RMSE have fairly high values, along with a R^2 of 59.4%

## Recommendations

Model Performance
-Overall, the model that performed best was the Tuned Random Forest Model. To further make this model more accurate and have better performance, more data inspection and model tuning is required.

