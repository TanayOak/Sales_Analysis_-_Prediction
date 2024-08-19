# Sales_Analysis_-_Prediction

The aim of this project is to predict sales pattern and know readily beforehand when to order and replenish inventories as well as plan for manpower and staffs.An accurate forecasting model can greatly increase store revenue and is generally of great importance to the organization as it improves profit as well as provides insights into the way customers can be better served. Managers can use sales prediction reports to identify market opportunities and areas where they could increase volume. To correctly forecast a future event, a machine learning model is trained on data from which it learns patterns that are used to predict future instances. One of the most valuable assets a store can have is data generated by customers as they interact with various stores. Within these data, lies important patterns and variables that can be modelled using a machine learning algorithm; and this can to a very high degree of accuracy to correctly forecast sales.

## Setting up the System:

Before we actually get into the Model Building phase, we need to ensure that the right libraries and frameworks have been installed in Google Colab Notebook or Jupyter Notebook. The below libraries are required to run this project:
* NumPy
* Pandas
* TensorFlow
* Keras
* scikit-learn(sklearn)
* Seaborn
* Plotly
* Matplotlib
* H5py
* Fbprophet

Dataset: Store sales historical data from “Rossmann Store Sales” Kaggle competition.

Steps of Predicting Sales:

1. Import and Load the Dataset file
2. Preprocess and Clean the Data
3. Create and Normalize Training and Test data
4. Build and Train the Models
5. Predict Sales for Test Data
6. Calculate Accuracy(r2_score)
7. Plot Graphs for Actual v/s Predicted Sales

## Import & Load Dataset

Link to the Dataset.csv -> "https://docs.google.com/uc?export=download&id=15GuwyGYyq1mjrYyPVV-j3B9d_Shm3_SI" 
# for direct download from drive- https://docs.google.com/uc?export=download&id=

![image](https://user-images.githubusercontent.com/88525549/187131494-fa93cd13-e249-4fa1-8de0-eb4dc42cac60.png)

## Analysis of Dataset

![image](https://user-images.githubusercontent.com/88525549/187131533-e8072c4d-9f75-4604-8e82-0ea1951ec877.png)

## Barplot

![image](https://user-images.githubusercontent.com/88525549/187131670-a3279b67-8cb4-45f9-a42b-5fa42baea931.png)

## Correlation Matrix Heatmap

![image](https://user-images.githubusercontent.com/88525549/187131702-3d305f1c-7ac7-4023-a56d-bb9c4fd32bcc.png)

1. Linear Regression
    Prediction on Test Data
    ![image](https://user-images.githubusercontent.com/88525549/187132278-7f00a69f-3589-4f7d-aac2-0776d2190d11.png)

2. XGBoost
    Prediction on Test Data
    ![image](https://user-images.githubusercontent.com/88525549/187132365-df119e52-fdd8-47dc-af61-3b6f2a3dd898.png)

3. Random Forest Regressor
    Prediction on Test Data
    ![image](https://user-images.githubusercontent.com/88525549/187132492-a0252dd2-7071-457f-a81f-18ef2e762776.png)

4. CatBoost
    Prediction on Test Data
    ![image](https://user-images.githubusercontent.com/88525549/187132622-d9b01caa-df4f-4411-af7a-f89de8dc48b5.png)
    
5. FBProphet
    Prediction of Trends
    ![image](https://user-images.githubusercontent.com/88525549/187132685-2e4ddeec-5371-42a0-81cb-0bd005364d7f.png)

# Conclusion

Sales forecasting is very crucial for every business, especially big ones and this process is very complex because there are lots of factors that should be taken into consideration. In order to implement achievable goals and successfully implement them, supermarkets chains always want to forecast sales. In this Mini Project, we used Machine Learning Algorithms like Linear Regression, Random Forest, XGBoost, CatBoost, LGBM (Light Gradient Boosting Machine), Stochastic Gradient Descent (SGD), LASSO (Least Absolute Shrinkage and Selection Operator) and LSTM(Long Short Term Memory) Recurrent Neural Network for sales forecasting, CatBoost performed better, as it had a higher R2 Score (Coefficient of Determination) and lower root mean squared error than the other models. Also, FBProphet was used for time series sales forecasting and finding trends in the data. The use of regression approaches for sales forecasting can often give us better results compared to time series methods.

# References

1. https://towardsdatascience.com/
2. https://stackoverflow.com/
3. https://www.kaggle.com/
4. https://datascience.stackexchange.com/
5. https://www.mdpi.com/2306-5729/4/1/15/pdf
6. https://machinelearningmastery.com/
7. Odegua, Rising. (2020). Applied Machine Learning for Supermarket Sales Prediction.


