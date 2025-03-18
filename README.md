# Project--Energy-Consumption-Prediction

-Overview
This project aims to predict energy consumption using regression models.The goal is to analyze various environmental and electrical parameters that influence energy usage and develop a predictive model to optimize consumption patterns. By leveraging data preprocessing, feature engineering, and model selection techniques, the project aims to provide insights that can help in energy efficiency planning for residential and commercial applications.

-Dataset Description
The dataset includes the following key features:
Appliance energy consumption (target variable)
Temperature and Humidity from multiple locations
Weather conditions (e.g., wind speed, pressure)
Light intensity and visibility
Time-related features (e.g., hour of the day, day of the week)

-Methodology:

1.Data Preprocessing
2.Handling Outliers
3.Feature scaling
4.Train-test split
5.Feature engineering

-Model Selection:
The following Machine learning regression models were implemented
1.Linear Regression
2.Decision Trees
3.Random Forest
4.Gradient Boosting (XGBoost)
5.Ridge Regression

-Hyperparameter tuning done for optimal Performance

-Performed Evaluation Metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared Score (R^2)

Results & Insights
.The Random Forest model achieved the best performance with an Highest R² score value.
.Weather conditions and indoor temperature were found to be the most influential factors in energy consumption.
.Feature importance analysis showed that humidity, temperature, and time of day significantly impact energy usage.
.The model struggled to predict sudden energy spikes, suggesting a need for further feature enhancements.

Conclusion
This project successfully demonstrates how machine learning can be used to predict energy consumption based on environmental and temporal factors. The insights gained can be applied to optimize energy usage in residential or commercial settings. Future improvements could include additional real-time data sources and deep learning models for enhanced accuracy.



