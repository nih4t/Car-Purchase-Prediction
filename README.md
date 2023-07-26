# Car Purchase Prediction 

![image](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/d8cf7882-90ea-4bff-b467-163d121cd7ad)


## Introduction

This project aims to predict whether a customer will purchase a car or not based on their age and estimated salary. A bunch of popular classification algorithms, are used for this prediction task.

In the automotive industry, understanding customer behavior and preferences is crucial for optimizing marketing strategies. Predicting whether a potential customer will make a car purchase can provide valuable insights into targeted advertising and sales efforts.

This predictive model can be utilized by social network platforms to deliver more relevant and personalized ads to users who are likely to purchase a car. By identifying potential car buyers, advertisers can focus their marketing budget on users who have a higher probability of converting, thereby increasing the efficiency and effectiveness of their ad campaigns.

## Dataset

The dataset contains the following columns:

- **Age**: The age of the customer.
- **Estimated Salary**: The estimated salary of the customer.
- **Purchased**: The target variable, where 1 indicates the customer purchased a car, and 0 indicates otherwise.


## Results

### Visualization of Train Set Predictions - Logistic Regression

![Train Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/06400fbe-4c30-4037-a3af-2addddc0caf3)

### Visualization of Test Set Predictions - Logistic Regression

![Test Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/584e398d-9d8e-4e36-97bb-771b489d54c4)


The logistic regression model performed well on both the training and testing datasets. The accuracy level of the model, which measures the proportion of correctly predicted outcomes, is 0.925. 

### Visualization of Train Set Predictions - K-nearest neighbors 

![Train Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/e6385dee-f1d6-4af9-9d71-95e782474930)

### Visualization of Test Set Predictions - K-nearest neighbors

![Test Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/15c47a1d-09ef-488d-8ef4-4acd892ccc97)

The K-nearest neighbors model performed well on both the training and testing datasets. The accuracy level of the model, which measures the proportion of correctly predicted outcomes, is 0.95.

### Visualization of Train Set Predictions - Kernel SVM

![Train Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/a5817bc3-5043-427e-9922-0e36df692af7)

### Visualization of Test Set Predictions - Kernel SVM

![Test Set Predictions](https://github.com/nih4t/Car-Purchase-Prediction/assets/82613166/fdc0443d-e122-4d12-b8f4-b7347bf9282e)

The Kernel SVM  model performed well on both the training and testing datasets. The accuracy level of the model, which measures the proportion of correctly predicted outcomes, is 0.95.


## Using the Predictions for Social Network Ads

The predictions from this model can be employed by social network platforms and advertisers to target potential car buyers. By integrating this predictive model into the ad delivery system, advertisers can selectively show car-related ads to users who are more likely to make a car purchase. This targeted approach can lead to higher conversion rates and better return on investment (ROI) for advertisers.
