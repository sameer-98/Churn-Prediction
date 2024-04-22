# Churn-Prediction

Churn prediction analysis is a widely used technique involving the use of machine learning models to predict whethe a customer will stay associated with an organization of the customer leaves. This technique is widely utilized by banks who wish to retain their customers. In this notebook we will carry out the study related to the trends in churn and what necessary steps can be taken to ensure its reduction . We will use Kaggle as the source for the data.

SCOPE
- Exploratory Data Analysis
- To predict whether a Customer continues with their account or closes it

The dataset contains imbalanced data as there are more samples for people who did not churn as compared to samples that churned. To tackle the problem of class imbalance we have employed to techniques.

- Used recall instead of accuracy as the evaluation metric
- Used SMOTE ENN as a sampling technique.

Kaggle Dataset: https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction