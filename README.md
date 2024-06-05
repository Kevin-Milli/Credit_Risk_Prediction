# Credit Risk Dataset

## Introduction

I chose to work on an important problem by exploring various datasets on Kaggle, and I stumbled upon the [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset).

Credit risks are commonly observed in areas of finance involving mortgages, credit cards, and other types of loans. There is always a chance that the borrower will not repay the amount. Traditionally, it refers to the risk that a lender will not receive the principal and interest due, resulting in a disruption of cash flows and increased collection costs. Therefore, properly assessing and managing credit risk can reduce the severity of a loss.

**Definition of "credit":**

- Credit is the ability to borrow money or access goods or services with the understanding that it will be repaid along with interest at a later date.
- Creditworthiness is how a lender determines the reliability of a borrower, to understand how likely they are to repay the money.

## Objective and Goal

The objective of the project is to analyze the loan_status variable. After analyzing the data and existing correlations with loan_status, an ML algorithm will be created to determine how accurately loan_status can be predicted from the provided data.

## Key Features

- `person_age`: Age of the individual applying for the loan.
- `person_income`: Annual income of the individual.
- `person_home_ownership`: Type of home ownership of the individual.
- `person_emp_length`: Employment length of the individual in years.
- `loan_intent`: The intent behind the loan application.
- `loan_grade`: The grade assigned to the loan based on the creditworthiness of the borrower.
- `loan_amnt`: The loan amount requested by the individual.
- `loan_int_rate`: The interest rate associated with the loan.
- `loan_status`: Loan status, where 0 indicates non-default and 1 indicates default.
- `loan_percent_income`: The percentage of income represented by the loan amount.
- `cb_person_default_on_file`: Historical default of the individual as per credit bureau records.
- `cb_person_cred_hist_length`: The length of credit history for the individual.

## Summary

After a thorough analysis and optimization, I trained a machine learning model that achieved an accuracy of 93% in predicting the default risk in loans. Although the model demonstrated good performance in identifying risky loans, there are still opportunities for further improvement. This work provides a solid foundation for financial risk management in lending, enabling more informed and targeted decisions.
