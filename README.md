# Data-Science-Final-Project
# Predicting When to Buy P&G Stock
# Nick Tufano

This projects uses a variety of machine learning tactics to see if it can sucessfully predict when to buy P&G stock on any given day. This project looks at three different types of machine learning to see if any are particularly successful. All models are trained solely on the the history of the stock price. Of 20 years of stock price data, 90% is used as a training set and 10% is used as a validation test. 

### This repository contains the historical data of Proctor & Gambles stock price frmo 2002-2022.
The data was downloaded from YahooFinance which can be found at https://finance.yahoo.com/quote/PG/history?p=PG 

## Video Link to Explanation of Code:
## Video Link to Presentation of the Project and Results

## Data Statistics
### General Statistics
As of 12/15/2022:  
There are 5035 days of data.  
The 20-year high of P&G is $165.35.  
The 20-year low of P&G is $28.52.  
P&G closed at $152.84 on 12/14/2022

### P&G Share Price 20-Year History
<img width="714" alt="image" src="https://user-images.githubusercontent.com/120423097/207971078-58c493a3-050c-4eb2-b668-dfcbe4c3045a.png">

### Distribution of Variables
<img width="743" alt="image" src="https://user-images.githubusercontent.com/120423097/207971358-6c3cd1b2-1161-4504-80c8-1462d494839f.png">

<img width="744" alt="image" src="https://user-images.githubusercontent.com/120423097/207971442-9c64d1cf-0e94-4243-a2d3-97e6898bca82.png">

### Correlation of Variables
<img width="605" alt="image" src="https://user-images.githubusercontent.com/120423097/207971529-ef4db7ee-bb64-4773-a67c-d6cc769961a8.png">

### Summary of Statistics
<img width="654" alt="Screen Shot 2022-12-15 at 4 13 29 PM" src="https://user-images.githubusercontent.com/120423097/207968342-6d0abdbd-3349-4af6-8d77-972796b13760.png">

## Data Organization

The data set is organizeed by date, open, close, high, low, adjusted close and volume. The descriprion of all the features is provided below.

### Features Description
<img width="511" alt="image" src="https://user-images.githubusercontent.com/120423097/207969719-b765e764-e394-413d-92b5-e4a68eab7980.png">

## Results

### Model Accuracy
<img width="669" alt="image" src="https://user-images.githubusercontent.com/120423097/207973034-603f71d6-69ba-400f-80ec-8aeda58726be.png">

From the above results we see that the SVC performed the worse. The best on the training set was the XGB Classifier, but looking at how it performed ont the validation test shows that the model is likely overfitting. The logistic regression performed the best, but still barely better than a 50/50 guess.

