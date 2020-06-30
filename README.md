# Project

## Loan-Prediction
Predict Loan Eligibility For Dream Housing Finance Company

# Table of Contents
* [Introduction](#Introduction)
* [Data Dictionary](#Data-Dictionary)
* [Aim of the Project](#Aim-of-the-Project)
* [Working with Dataset](#Working-with-Dataset)
* [Conclusion](#Conclusion)

## <a name="Introduction"></a>Introduction
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.


## <a name="Data Dictionary"></a>Data Dictionary
|      Variable     |                   Description                  |
|:-----------------:|:----------------------------------------------:|
| Loan_ID           | Unique Loan ID                                 |
| Gender            | Male/ Female                                   |
| Married           | Applicant married (Y/N)                        |
| Dependents        | Number of dependents                           |
| Education         | Applicant Education (Graduate/ Under Graduate) |
| Self_Employed     | Self employed (Y/N)                            |
| ApplicantIncome   | Applicant income                               |
| CoapplicantIncome | Coapplicant income                             |
| LoanAmount        | Loan amount in thousands                       |
| Loan_Amount_Term  | Term of loan in months                         |
| Credit_History    | credit history meets guidelines                |
| Property_Area     | Urban/ Semi Urban/ Rural                       |
| Loan_Status       | (Target) Loan approved (Y/N)                   |

## <a name="Aim of the Project"></a>Aim of the Project
Company wants to automate the loan eligibility process in real time based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 

## <a name="Working with Dataset"></a>Working with Dataset
 - Initially the dataset is loaded and initial missing-values imputations, pre-processing, feature engineering, and exploratory data analysis is done.
 - Used the classification algorithms to classify the data:
    - Logistic Regression
    - Gradient Boosting Classifier
  
## <a name="Conclusion"></a>Conclusion
The Logistic Regression Algorithm was found to be the best performing generalized model in Predicting Loan Defaulters based on the records.
