# Renovation_Cost_Regression_Analysis
Overview
This repository contains code for renovating cost analysis based on a dataset of housing data. The analysis includes data preprocessing, feature engineering, and building and optimizing regression models for predicting renovation costs.

Data Analysis
The analysis begins with importing necessary libraries for data manipulation, visualization, and model building. The dataset (housing_data.csv) is loaded into a Pandas DataFrame (df). Basic data visualizations are provided, giving insights into the geographical distribution of property values.

Preprocessing
Data preprocessing involves encoding categorical variables, scaling numerical features, and standardizing the data. Label encoding, MinMax scaling, and Power Transformer are applied to ensure the data is suitable for model training.

Regression Model
The dataset is split into training and testing sets, and a Gradient Boosting Regressor model is trained. Cross-validation is performed to evaluate the model's performance, and the mean R^2 score and RMSE (Root Mean Squared Error) are calculated.

Optimizing Model
Feature selection is carried out using Recursive Feature Elimination (RFE) to find the optimal number of features. The analysis is performed iteratively, and the impact on the model's performance is evaluated. The final selected features and their impact on the model's performance are presented.

Conclusion
The README concludes with a summary of the optimal features, their impact on the model, and a compiled score of RMSE for different feature sets.

Feel free to explore and adapt the code for your specific use case. If you have any questions or feedback, please open an issue or reach out to the repository owner.
