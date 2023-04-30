# credit_card_approval
# Credit Card Approval Project - Data Analysis

This project aims to develop a machine learning model to predict credit card approval for potential customers based on their application data. In this analysis, we will explore and preprocess the data before building and evaluating our machine learning model.

## Dataset

The dataset contains 1548 instances and 19 attributes, including both numerical and categorical variables. The target variable is the credit card approval status, which can take two values: "1" for approved and "0" for rejected.

## Data Analysis

We begin by importing the necessary Python libraries, including NumPy, Pandas, and Matplotlib. We load the dataset into a Pandas DataFrame and perform some basic exploratory data analysis, including:

- Checking for missing values
- Descriptive statistics
- Data distribution
- Correlation analysis

We also visualize some of the key features using Matplotlib to gain a better understanding of the data distribution and relationship between variables.

## Data Preprocessing

After analyzing the dataset, we preprocess the data by performing the following tasks:

- Handling missing values
- Converting categorical variables to numerical
- Scaling numerical variables
- Splitting the data into training and testing sets

We use the NumPy and Pandas libraries to perform these tasks and prepare the data for machine learning modeling.

## Machine Learning Modeling

We then build and evaluate several machine learning models to predict credit card approval using the preprocessed data. We use a variety of algorithms, including Logistic Regression, Decision Trees, K - Nearest Neighbour and XGBoost .

We evaluate the performance of each model using accuracy, precision, recall, F1-score, and ROC curve analysis.

## Conclusion

In this analysis, we explored and preprocessed the credit card approval dataset before building and evaluating several machine learning models. We achieved the best performance using the Random Forest algorithm, which achieved an accuracy of 85% on the test set. The results of this analysis demonstrate the feasibility of using machine learning to predict credit card approval and can be useful for credit card companies in assessing potential customers' creditworthiness.
