# ML_Churned_Users_Prediction

# I. Introduction

## 1. Business question

One ecommerce company has a project on predicting churned users in order to offer potential
promotions.

## 2. Dataset

An attached file is the dataset that is offered by the company (churn_predict.csv).

![alt](https://github.com/khoatna065/ML_Churned_Users_Prediction/assets/167158955/6858c807-796f-444f-ac8c-03899d4824e0)
![alt](https://github.com/khoatna065/ML_Churned_Users_Prediction/assets/167158955/b2b78cd6-59c4-4463-88d9-baddf013821e)

## 3. Method

Supervised learning with Scikit-learn on Python

# II. Process

1. Import libraries and dataset
2. Check imbalanced data
- The churned variable is about 16.84%  of total → Quite imbalanced so still process ML model as normal.
3. Data wrangling
- No duplicate values is found.
- The variables have missing values: Tenure, WarehouseToHome, HourSpendOnApp, OrderAmountHikeFromlastYear, CouponUsed, OrderCount, DaySinceLastOrder. ⇒ replace null values with appropriate values.
- Change data type of CustomerID into object.
4. EDA 
5. Feature transforming

# III. Model training and evaluation

- Encoding and normalizing dataset
- Apply to models: Logistic Regression, Decision Tree and Random Forest

# IV. Conclusion

- In this project, I build three models, Logistic Regression, Decision Tree and Random Forest to predict the churned users . The Decision Tree model is a very good performance by the model balanced accuracy which was found to be 0.9178.
- In the Decision Tree, the training-set balanced accuracy score is 1.0 while the test-set accuracy to be 0.9178. These two values are quite comparable. So, there is no sign of overfitting.
- The confusion matrix and classification report yields very good model performance.
