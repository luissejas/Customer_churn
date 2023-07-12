# Customer churn Analysis

Customer churn refers to the phenomenon where customers discontinue their relationship or subscription with a company or service provider. It represents the rate at which customers stop using a company's products or services within a specific period. Churn is an important metric for businesses as it directly impacts revenue, growth, and customer retention.

In the context of the Churn dataset, the churn label indicates whether a customer has churned or not. A churned customer is one who has decided to discontinue their subscription or usage of the company's services. On the other hand, a non-churned customer is one who continues to remain engaged and retains their relationship with the company.

For data preprocessing, the following was applied:
  - Checking for outliers in the data
  - Data normalization
  - Generation of dummy variables of categorical features
  - Checking if there multicollineariy in the dataset

After data preprocessing, a Random Forest Classifier was employed achieving an accuracy score of 99%.
