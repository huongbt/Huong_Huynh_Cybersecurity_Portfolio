# Huong's Data Science Project Porfolio
Hi, My name's Huong Huynh. I am a Data Scientist who is passionate in extracting insights from data and learning new techniques to help this process more efficient.

# [Project 1: Ads Click Through Rate Prediction](https://github.com/huongbt/Ads-CTR-Prediction)

Click-through rate (CTR) is a very important metric for evaluating ad performance of online advertising. Ads Click Through Rate is the ratio of how many users clicked on an ad over total number of users viewed that ad. Building this model to predict Ads click will help companies in finding the best ad for their target audiences. 

In this project, our task is to predict whether the user will click on the ad or not. I trained a Machine Learning model to find relationships between the independent variables of all the users who click on ads.

# [Project 2: Creditcard Score Classification](https://github.com/huongbt/Credit-Score-Classification)

A credit score tells lenders about your creditworthiness. Companies use credit scores to make decisions on whether to offer you a mortgage, credit card, auto loan, and other credit products. With fast incresing in using Machine Learning and Deep Learning for most of our aspect of lives, banks and credit card companies are not out of these trends. They use Machine learning algorithms to classify their customers's credit card score into different levels based on their customers's historical data.

* Build a classifier to classify credit score into three different labels (Good, Standard, Poor). 
* Train data with Random Forest Classifier and Xgboost Classifier. O
* Fine tune hyperparameters using RandomizedSearchCV and GridSearchCV to reach the best model.

Data used in this project is based on the credit score classification submitted by Rohan Paris on Kaggle: https://www.kaggle.com/parisrohan

# [Project 3: Store Sales Time Series Forecast](https://github.com/huongbt/store-sales-time-series-forecast)
![](/images/sale_forecast_i1.png)

Used time-series forecasting to forecast store sales on thousands of items sold at different stores of Corporación Favorita, a large Ecuadorian-based grocery retailer. For grocery stores, more accurate forecasting can decrease food waste related to overstocking and improve customer satisfaction. 

* Models used in the project: Facebook Prophet and Xgboost. Facebook Prophet produced the much better result than Xgboost.
* Combined many different data set from the competition such as oil price, holidays,...
* Forecast each product family at each store (there are 33 families and 54 stores) and combined the result together.
* Used Mean absolute percentage error to evaluate model performance. 

# [Project 4: Power Forecast using stacked LSMT from Tensoflow](https://github.com/huongbt/Power_forecast_Tensorflow)

In this project I used stacked LSTM from Tensorflow to forecast future power consumption. This could be helpful in predicting number of installed batteries and scheduling charging time in order to increase limit of power usage for data centers.
* Normalized data used MinMaxScaler from sklearn
* Trained model LSTM consists of two layers. 
* Tried many different optimizers function such as sgd, adam and Rmsprop, and Rmsprop produce the smallest loss error. Loss function I used here is mean absolute error.
* There is potential to improve on forecast error with increase number of epochs and finetune model architecture. Most of loss curve are not flat yet.


