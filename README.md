# Airbnb Price Prediction
This project analyzes and predicts Airbnb rental prices in San Diego using real-world data. The goal was to build a model that estimates listing prices based on features like location, property type, and availability. During the process, the dataset presented several challenges — including missing values, irrelevant columns, and inconsistent data formatting — which required extensive cleaning and preprocessing. After refining the dataset, various machine learning models were tested to identify patterns and factors influencing pricing. The project highlights the importance of data quality and preprocessing in achieving accurate predictions for real estate and hospitality analytics.

## Skills Used 
- Used Pandas to clean the dataset and preparing it for model training. 
- Used KMeans to cluster locations together and find patterns within those location clusters (using `latitude` and `longitude` data points).
- Used `XGBRegressor` as my model and fine tuned it for optimal results.
- Normalized all of my data using `numpy` for accurate results.

## Future Improvements 
My goal is to investigate ways to improve the model accuracy. A way I might do this is look for a better dataset that has more consistent values, or find a better model than the `XGBRegressor`. 
