# Taxi-Demand-Prediction
This repository explain how to building taxi demand predicition model by using python, model can help provide insight in order to determine the number of units to deploy by adjusting the predicted demand results, so TLC as Taxi Operator can reduce demand and supply imbalances more measurably.
## Steps
1. Data understanding
2. Data cleansing
3. EDA (Exploratory Data Analysis)
4. Data preprocessing
5. Modeling
6. Model interpretation
7. Business recommendation
## Summary
1. The dataset consist of 3,599,400 rows & 22 columns, and after cleansing the new dataset without missing value and duplicated value becomes 3,416,987 rows and 22 columns or 95% from original dataset. 
2. Taxi demand predicition model using Random Forest Regression because it has the lowest RMSE score after compared to others model (Linear Regression and Decision Tree Regression)
3. There are top 2 feature importance (pickup_cluster and hour), focus with these features because they have more contribution in model prediction compared to others features
## Business recommendation
1. By using the Random Forest Regression model, TLC can focus on cluster pick_up data and hours to determine the number of units to deploy by adjusting the predicted demand results, so TLC can reduce demand and supply imbalances more measurably.
2. Create a route rotation policy for drivers so that units are not spread over certain locations.
3. Make a balanced policy for drivers based on the number of trips and mileage.
