# Summary
* Cleaned over 163,000 data
* Wanted to predict hospital prices to see if prices would increase in the future 
* I used Log transformation on this model to improve the data set as it had a log curve. 

# EDA
![](images/Aveage_Total_Payment_Distribution_Plot.png)
![](images/Linear_Regression_Scatter_Plot.png)
![](images/Log_Payment_Distribution_Plot.png)
![](/images/Random_Forest_Scatter_Plot.png)

# Model

I split the data to a 80% training data and 20% test data.
The models I used are:
* Linear Regression
* Random Forest Regressor

# Result:

I used three different metrics to see the outcome: Mean Absolute Error, Mean Squared Error, and Root-Mean Square Error

Linear Regression errors:
* MAE: 0.056724061557420255
* MSE: 0.007312409414163595
* RMSE: 0.08551262722056664

Random Forest Regressor:
* MAE: 0.05155625429463174
* MSE: 0.00684927725933619
* RMSE: 0.08276036043503067
