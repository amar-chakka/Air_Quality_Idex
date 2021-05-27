# Air_Quality_Idex
Determine Air_Quality_Idex using different neural networks

## Objective:
This dataset is intended for regression tasks.
Use this data set to train a model able to predict the air pollution index on a specific day in
the future.

This project was created as a part of the INSAID Term project to help customer in detecting Air Quality index by analyzing the data set.  

In this project the outcome is air quality score. 

We are going to look at a Data set which contains 13 independent variables [object , int & float type] & 1 Target variable [int type].

2 features have different categories, however we created columns under one hot encoding. For Date object created year, month, date and hour columns.

All features  are already scaled using standard scaler.

There are outliers in snow_p_h & rain_p_h features, Below box plots shows it.
Plotted a correlation matrix
dew_point and visibility_in_miles are same and redundant, so removed 1 feature.


![enter image description here](https://github.com/amar-chakka/Air_Quality_Idex/blob/0b2067db1e1e7cc6419522fe196d8ef895ccddb2/Training_Validation%20Loss%20plots.png?raw=true)


Below are the different validation scores for different regression networks

model1 : 6933.0840  [Best score]
model2 : 7059.7026
model3 : 7855.0635
model4 : 7201.8007

Conclusion:
•I analyzed the characteristics and distribution of data in brief.
•I investigated in-depth the features which to retain and which to discard.
•I performed model development by using different networks of a variety of hidden layers, neurons, regularizers.
•I observed mixed results as we started experimenting with different networks .
•This model will help the community in predicting air pollution quality to a RMSE of 83.

To check out my notebook, please click [here](https://github.com/amar-chakka/Air_Quality_Idex/blob/0b2067db1e1e7cc6419522fe196d8ef895ccddb2/AirQualityIndex_DL.ipynb).
