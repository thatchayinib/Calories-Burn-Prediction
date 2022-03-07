# Calories-Burn-Prediction

The fast food consumption rate is high nowadays and has led to the intake of unhealthy food. This leads to various heath issues such as obesity, diabetes , an increase in blood pressure etc. This project focuses on the calories burned in accordance with the duration provided and heart rate during the exercise period. This research helps in providing the benefits of a machine learning algorithm over predicting the calories burned.

# libraries 
Numpy

Pandas

Matplotlib

Plotly

Seaborn

Scikit learn

# Dataset
Exercise.csv - we have 15000 rows and 8 columns

calories.csv - we have 15000 rows and 2 columns

1.User_ID : The ID of the person which is unique.\ 2.Gender : Gender of the person.\ 3.Age : Age of the person.\ 4.Height : Height of the person in cm .\ 5.Weight : Weight of the person in kg .\ 6.Duration : Duration of the person's exercise/activity in min.\ 7.Heart_Rate : Heart rate per min of the person.\ 8.Body_Temp : Body temperature of the person in celsius .\ 9.Calories : Calories burned in kilo calories.

# Handling outliers

For detecting Outliers - IQR Method

For Removing Outliers - Quantile based Flooring and capping

# Data Visualization

Here we have visualize the charts based on some categories.Here by some samples

First we are going to find correlation between the dependent and independent variables.

![image](https://user-images.githubusercontent.com/101081747/156975487-9a98999e-da76-4e21-bdd6-900bc81ccc26.png)

As we can observe, old individuals have burned more kilocalories in compare of two other age groups.And the young persons are the least in burning kilocalories which is a surprise! Another interesting thing is, females in all age ranges performed very similar.In other words, they burned same amount of kilocalories in average.But for males, old group outperformed and the youth have the weakest performance. 

![image](https://user-images.githubusercontent.com/101081747/156975602-f21d2b0d-2837-484f-a5e9-e5abb0cc8865.png)

As we can see , the exercise duration of each group is pretty identical.Every group have the same interquartile range , median and so on. In addition, the duration is very similar for males and females in old and middle-aged groups.But in youth, males outperformed. Another tip is, the median exercise duration of this dataset is about 15 minutes 

![image](https://user-images.githubusercontent.com/101081747/156975657-14993330-a29c-475f-bb9e-fb7decb8ec91.png)

As we can see the Categorized_BMI is identically distributed between age groups(the sequence is identical, for example in both Normal and Overweight ; Young comes first , 'Middle-Aged` comes second , etc.) An interesting thing is , about 50% of old individuals have Normal weight and another 50% are Overweight. 

![image](https://user-images.githubusercontent.com/101081747/156975717-c50ba4f3-74f0-492a-8d1e-32e402ef59ec.png)

we plotted the scatter plot for the duration of exercise and heart rate on size of calories.From that when the people do more exercises more heart rate and theor calories also burning high. 

![image](https://user-images.githubusercontent.com/101081747/156975768-c237ca03-d0d6-496e-835d-3c7312d0bf1a.png)

# Building Regression Model

Since it is a Regression Dataset we are going to use different algorithms

•	Linear Regression

•	RandomForest Regressor

•	AdaBoost Regressor

•	Decision Tree Regressor

•	Ridge Regression

•	XGBoost Regression

# Regression Evaluation Metrics

we use diffrent evaluation metrics to Evaluate our model

•	MAE

•	MSE

•	RMSE

![image](https://user-images.githubusercontent.com/101081747/156975969-ec8d1d67-68df-4a75-a946-8fb285e0ff59.png)

By plotting the Mean Absolute Error value it shows that RandomForest and XGBoost Regressor giving better results when comparing with other algorithms so both be the better for MAE

![image](https://user-images.githubusercontent.com/101081747/156976082-e75c8f69-3200-44c8-8a0d-05f92527e1af.png)

By consideration of Root Mean Squared Error both Random Forest Regressor and XGBoost Regression giving better prediction for RMSE.

By comparing MAE, MSE, RMSE of all algorithms RandomForest and XGBoost Regressor will make the better prediction when compared to other algorithms
