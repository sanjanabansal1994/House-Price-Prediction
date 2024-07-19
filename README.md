This project is to predict House Sale Price based on many features.

First I looked upon the distribution of sales price, to see if it is uniformly distributed or not.
<img width="904" alt="Screenshot 2024-07-19 at 2 22 32 PM" src="https://github.com/user-attachments/assets/fd15c837-0858-4cef-97b1-f18b7ed239ba">  

Then I used Linear Regression, XGBoost Regressor, Support Vector Regressor, RandomForestRegressor to predict the price. 

I used GridSearch along k-fold cross validation techniques to find the best estimators of individual method.

<img width="582" alt="Screenshot 2024-07-19 at 2 27 39 PM" src="https://github.com/user-attachments/assets/514b89a5-9a1d-487f-bbe5-e9479653b624">

As XGBoost is performing better in this problem. I checked out some performance metrics likes $R^2$, residual plot distribution etc given below:  
<img width="235" alt="Screenshot 2024-07-19 at 2 31 40 PM" src="https://github.com/user-attachments/assets/e5364d2a-e380-44fb-aeae-37b9ba7b5295">

<img width="611" alt="Screenshot 2024-07-19 at 2 32 11 PM" src="https://github.com/user-attachments/assets/edb8f275-173e-4200-9e93-f8baf4c654ed">

We can conclude that we will be able to predict the price of house with very high accuracy shown in below predicted value vs Actual values plot:

<img width="595" alt="Screenshot 2024-07-19 at 2 37 05 PM" src="https://github.com/user-attachments/assets/62242097-8c5c-4be7-baad-a991c6665944">

