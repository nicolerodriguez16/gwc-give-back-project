# Exploratory Data Analysis/ Feature Engineering / ML Process
Based on the columns with excessive null values in the Graduation Results dataset, I either dropped the columns or filled the missing values where appropriate. I also created a new column to represent the borough of the school using the geographic subdivision information and converted relevant columns to float data types to ensure consistency and compatibility for modeling.

R- Squared: 0.9523
    High R-squared value signifies that the model performs well and can predict the label accurately. However, overfitting may occur, leading to inaccurate predictions on new or unseen data.
Mean Squared Error: 23.8185
    Shows how far off my predictions are from the actual values using the Mean Squared Error.
Root Mean Squared Error:4.8804
    The square root of the mean squared error (RMSE) shows how far the predictions are from the actual values with the squared MSE
Mean Absolute Error: 2.7407
    The mean of the absolute differences between the predicted values and the actual values.
