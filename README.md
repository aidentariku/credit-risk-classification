# Credit Risk Classification

This project aims to build a machine learning model to predict the creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services company. The dataset used in this analysis is stored in `lending_data.csv` and contains various features such as loan size, interest rate, borrower income, and more. The target variable, `loan_status`, indicates whether a loan is healthy (0) or has a high risk of defaulting (1).

## Getting Started

To get started with this project, clone the repository to your local machine and navigate to the `Credit_Risk` folder. Ensure that you have Python installed along with the necessary libraries such as pandas, numpy, scikit-learn, and imbalanced-learn.

## Data Preparation

The first step involves loading the dataset into a DataFrame and separating the features (`X`) from the target (`y`). The data is then split into training and testing sets using a 75/25 split ratio.

## Data Resampling

Due to class imbalance in the target variable, resampling techniques are applied to address this issue. The RandomOverSampler from the imbalanced-learn library is used to balance the classes by oversampling the minority class.

## Model Training and Evaluation

A logistic regression model is trained using the resampled training data and evaluated on the testing data. Performance metrics such as precision, recall, and F1-score are calculated using a classification report to assess the model's predictive capabilities.

## Conclusion

Overall, this project demonstrates the process of building and evaluating a machine learning model for credit risk classification. By following the steps outlined in the analysis, stakeholders can gain insights into the creditworthiness of borrowers and make informed lending decisions.
# credit-risk-classification
