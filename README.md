# Customer_Conversion_Prediction
This Project Was customer Conversion Prediction. 

# Project Goal
The goal of the Customer Conversion Prediction project is to build a machine learning model that can predict whether a client will subscribe to the insurance based on their demographic and marketing data. The project aims to help the insurance company identify the customers that are most likely to convert, so that they can be targeted via call and the cost of telephonic marketing campaigns can be reduced. The historical sales data provided will be used to train and evaluate the performance of the machine learning models. The analysis of the model will be done to identify the important factors that contribute towards the conversion and the AUROC metric will be used to evaluate the model's performance. The main objective of the project is to develop an accurate and efficient model that can aid the insurance company in improving its sales conversion rate and reducing marketing costs.

# Project Aproach
For this project, I utilized Google Colab as my integrated development environment (IDE) for programming in Python. Google Colab is a robust tool provided by Google that is well-suited for implementing machine learning algorithms, performing data analytics and cleaning operations, and developing data science models.

# Project Implementation Steps:
# 1.Libraries Import and Load Dataset
We have imported requrired libraries and also loaded dataset

# 2.Clean Dataset
we have used functions like remove duplicates,dropped null values,missing values,check data type and removal of outlires.

# 3.Exploritory Data Analysis
For the good model fit and accuret prediction we've explore the data and done Univariate Analysis, Bivariate Analysis, Correlation Check. Data type check and take dummies.

# 4.Encoding
we have used Label and one hot encodeing for this features['job', 'marital', 'education_qual', 'call_type', 'mon', 'prev_outcome']

# 5.Split Dataset
SMOTE Oversampling we are using due to imbalence data

0 - 39477

1 - 29496

# 6.Scalling
We used StandardScaler.

# 7.Models
We used Linear regression, K nearest neigbors, Decision Tree, xgboost and Random Forest.

# 7.1.Model Evaluation
We are going to comapre auroc curve
model Evaluaton.

# Save The Model
we use  pickle package to save the model.

# Conclusion
Based on the results obtained from the evaluation of the three classification models (Logistic Regression,KNN, XGBoost, Random Forest and Decision Tree Classifier) on the given historical data, Random forest outperformed the other models with the highest accuracy score of 93.91% and the highest AUROC score of 0.987.

This implies that  Random Forest is a suitable model for predicting whether a client will subscribe to the insurance or not. It is recommended to deploy this model in the production environment to accurately target potential customers and optimize marketing costs.

However, further analysis is recommended to identify the important features contributing to the model's performance and to fine-tune the model for better results.
