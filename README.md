# Black-Friday-Sales-Prediction-using-PYTHON

Black Friday Sales Prediction
In this competition my task is to predict the purchase amount in test.csv. Through the dataset, I want to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month. Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers againstdifferent products¶


Kaggle Dataset link :- https://www.kaggle.com/c/gb-black-friday-sales/overview
My Kaggle submission score- 0.67

Below are each model predictions
Linear Regression 2527.2749990446146 ,
Decision Tree 3574.947791410736 ,
Random Forest 3574.947791410736 ,
XGBoost 2609.0666358339413 ,
I have also founded Neural network model prediction as 3589.629045206134 which is again not good , hence XGBOOST is best
We can see that XGBoost has best model predictions as its lowest , XGBoost is performing the best so I have taken XGBoost as my final submission

What can be done¶
No improvement with neral network based model,but can be improved by tuning hidden layer sizes, Due to infrastructure issue , I was unable to build large complex neural nets
