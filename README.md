# Loan Risk Analysis - MLZilla Competition
### Secured 2nd position among a pool of 500 students nationally.
### Detailed steps of model creation are given in the ppt.

## Problem Statement

Credit scoring and loan sanctioning are critical processes in the lending industry. Credit scoring assesses an individual's or business's creditworthiness using a numerical credit score, helping lenders decide on loan approvals and terms. Loan sanctioning involves evaluating loan applications, considering creditworthiness, income, employment, and other factors, ultimately determining loan approval and terms.

Machine learning is increasingly applied to these processes, utilizing historical data to predict loan default and assess borrower creditworthiness. Participants can use the provided dataset creatively to benefit the financial institution, employing various data modeling and machine learning tools and techniques as long as they are justified.

## Proposed Work
Our work proposes two main methodologies: one is a tableau report, which provides detailed data analysis on the difference between people who are Default(Charged Off) and **potentially** good loans (Current). Another is a Machine Learning model that predicts defaulters, which would aid the financial industry in preventing financial loss.

## Tableau Report
![image](https://github.com/rounaccc/Loan-Risk-Analysis/assets/85012501/3569f40f-6d55-41d1-a3f1-9ca7b8127707)

- [Tableau report link](https://public.tableau.com/app/profile/hetvigandhi/viz/LoanRiskAnalysis_16745696721300/LoanRiskAnalysis)

## Demo


https://github.com/rounaccc/Loan-Risk-Analysis/assets/85012501/534b7523-d4bd-4d93-9ff8-46c902ba7ce4



## Model Creation
![image](https://github.com/rounaccc/Loan-Risk-Analysis/assets/85012501/1af6925b-f9ea-48ce-84c8-cf4483e2c5b8)

## Our Analysis
- The model predicted a few of the ‘Current’ labels as Defaulters.
- There can be two POVs:
1. 23 could be the potential number of defaulters who won’t be able to repay the loan. Thus a good note to prevent losses by not giving them the loan.
2. There could be a minor precision error in the model, but it won’t affect much since it predicted only 23 labels as defaulters, which is not even 0.1% of the dataset.





