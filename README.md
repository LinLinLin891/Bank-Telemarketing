Topic: Bank Telemarketing data analysis
Analyzing the records of this telemarketing campaign, we would like to know whether Telephonic marketing campaign is effective in customer acquisition.

Objective of the Project:
1: Customer Segmentation (Identify customer groups most receptive to term deposit offers)
2: Campaign Optimization (Determine the most effective communication channels and contact frequency)
3: Predictive Modeling

Data source: https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets

The dataset contains 45,211 rows and 17 columns. The target variable in this dataset is y, which is a categorical variable that takes on the value of either “yes” or “no” for whether the customer has subscribed to a term deposit as a result of the current marketing. And there are 16 predictor variables related to the customer’s demographic information and financial status, and the previous and current marketing campaign results for customers. In terms of data type, there are 7 numerical variables and 9 categorical variables.

Using Lasso Variable Selection to split data into training dataset and testing dataset
Predictive Modeling:
Logistic Regression Model
Cross Validation
SVM
Decision Tree
Random Forests
k-nearest neighbors
