
# Ecommerce Fraud Detection

E-commerce fraud detection systems are designed to protect online businesses and their customers from various forms of fraudulent transactions and activities.


## Overview

Ecommerce fraud detection is a critical component of online retail operations. With the growing popularity of online shopping, fraudulent activities have also increased. This project aims to develop an effective fraud detection system to protect the business and customers from fraudulent transactions.

## Data Preprocessing

- [Data Sources](#data-sources)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Encoding Categorical Data](#encoding-categorical-data)
- [Data Splitting](#Data-Splitting)
- [Model Selection and Evaluation](#Model-Selection-and-Evaluation)
- [Classification Report](#Classification-Report)



## Data Sources
  
  Source :-  Kaggle datasets

  This Datasets consists of 2 csv files both containing information on ecommerce transactions made by customers.
    
   

```bash

   The 2 datasets are : 
            Customer details     :-   Information about customers and the transactions made by the customers. It tells whether the customer is fraud.
            Transaction details  :-   Information about all the transaction and the order fullfilled details.


```


## Data Cleaning
    involved - 
      
       *  Handling Missing Values
       *  Handling Duplicate Values



## Feature Engineering
    Finding out which features are helpful for building the ML model. Selecting those features and transforming them in the way we use them in the model training.

    
    As we are finding the Frauds in the datasets - True / False
    So this comes under `BINARY CLASSIFICATION`.

    --> Dependent Varaible  - Fraud  (from customer details)
    --> Independent Varible - rest of the variables

    These termed as X, y for using them in the training of the model.



## Encoding Categorical Data
    The categorical data was encoded into numerical values by using label encoding.


## Data Splitting
we will train our models using split_train_test by splitting the whole data into :-

`Trainig Data` - training data is the subset of original data that is used to train the machine learning model. here we take 80% of the original data.

`Testing Data` - testing data is rest of the trainng data, used to check the accuracy of the model. i.e., 20%



## Model Selection and Evaluation
  Binary Classification : 
      
      Binary classification involves categorizing data points into one of two classes. Here we are categorizing the data into Fraud(spam / not spam)


  There are so many Classification Algorithms 
  - [Logistic Regression](#Logistic-Regression)
  - [Support Vector Machine](#Support-Vector-Machine)
  - [Decision Tree](#Decision-Tree)
  - [Random Forest](#Random-Forest)
  - [KNeighbours](#KNeighbours)



## Classification Report

  By Analysing the accuracies of all the algorithms and the Classification Report, 

  Concluded that `Decision Tree` and `Random Forest` gives us the accurate model of Accuracy - 99%
  




## Conclusion
This `E-commerce fraud detection` project represents a significant step toward safeguarding the integrity of online transactions. We hope that our work serves as a valuable resource for the E-commerce community and inspires further advancements in the field of fraud detection. As we look to the future, we remain committed to improving our model's accuracy and effectiveness in the ever-evolving landscape of E-commerce fraud prevention.







