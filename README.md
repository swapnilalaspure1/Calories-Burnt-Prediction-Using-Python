# Calories-Burnt-Prediction-Using-Python

Calories Burnt Prediction Project Summary:
1. Data Collection & Processing:
Imported necessary libraries for analysis and machine learning.
Loaded two datasets: 'calories.csv' and 'exercise.csv'.
Combined datasets based on the 'User_ID' to create a unified dataframe.
Checked data shape, information, and presence of null values.
2. Data Analysis:
Explored statistical measures for numeric columns.
Visualized gender distribution using a count plot.
Analyzed skewness for numeric columns and plotted Probability Density Function (PDF) and Quantile-Quantile (QQ) plots for each.
3. Data Visualization:
Plotted PDF and QQ plots for columns like Age, Height, Weight, Duration, Heart Rate, Body Temp, and Calories.
4. Correlation Analysis:
Constructed a heatmap to visualize correlations between different features.
Identified that Duration, Heart Rate, and Body Temperature are highly correlated with Calories.
5. Data Preprocessing:
Converted categorical 'Gender' values to numerical values (0 for male, 1 for female).
Removed outliers using the IQR (Interquartile Range) method.
6. Model Building:
Defined features (X) and target variable (Y).
Split the data into training and testing sets.
Applied feature scaling using StandardScaler.
Utilized XGBoost Regressor and performed hyperparameter tuning with Randomized Search CV.
7. Model Evaluation:
Predicted calories on the test set.
Evaluated the model using Mean Absolute Error (MAE), R-squared value, and Root Mean Squared Error (RMSE).
Plotted Actual vs Predicted values for visualization.
8. Conclusion:
The XGBoost model, after hyperparameter tuning, demonstrated good performance in predicting calories burnt based on various features.
Visualization aids, such as PDF and QQ plots, were used to understand data distributions and identify correlations.
The project involved data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning model implementation.
9. Recommendations:
Consider further exploration and feature engineering for potential improvements.
Continue refining the model with additional data or alternative algorithms.
10. Future Work:
Explore additional machine learning models for comparison.
Incorporate user feedback and domain knowledge to enhance model accuracy.
This summary provides a brief overview of the key steps and findings in your calories burnt prediction project.
