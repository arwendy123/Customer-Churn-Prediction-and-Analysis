# Customer-Churn-Prediction-and-Analysis

This project focuses on predicting and analyzing customer churn in a telecommunications company. Customer churn refers to the phenomenon of customers discontinuing their relationship with a company, which can have significant financial implications. The objective of this project is to develop a machine learning model that can accurately predict customer churn based on various features and identify the key factors contributing to churn.

The project involves several steps, including data exploration and preprocessing, feature engineering, model training, and evaluation. The dataset consists of numerical and categorical features such as account length, total day charge, number of customer service calls, and others. The dataset also has an imbalance between churned and not churned customers, with only 14.1% of the total samples belonging to the churned class.

To address the class imbalance, different techniques such as resampling and SMOTE (Synthetic Minority Over-sampling Technique) are employed. The features are normalized and transformed using techniques like CountVectorizer for categorical features and StandardScaler for numerical features. The dataset is then split into training and testing sets.

Two machine learning algorithms, namely XGBoost Classifier and Random Forest Classifier, are implemented and evaluated. The XGBoost model uses the scale_pos_weight parameter to balance the classes, while the Random Forest model uses class weights. The models are trained on the training data and evaluated on the testing data using accuracy and recall scores.

The XGBoost Classifier achieves a train accuracy of 1.0, a test accuracy of 0.95, and a recall score of 0.73. On the other hand, the Random Forest Classifier achieves a train accuracy of 0.97, a test accuracy of 0.91, and a recall score of 0.72. The importance of features is also analyzed, and it is found that total_day_charge and number_customer_service_calls are the most important features for predicting customer churn.

Overall, this project aims to provide insights into customer churn behavior and develop a reliable predictive model that can help the telecommunications company identify customers at risk of churn and take proactive measures to retain them. The findings and methodology can be valuable for other industries facing customer churn challenges as well.
