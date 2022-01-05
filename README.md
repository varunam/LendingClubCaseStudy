# Lending Club Case Study
> Understanding the driving factors (or driver variables) behind loan  default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Table of Contents
* [Approach] Data Cleaning --> Sanitisation --> Univariate Analysis --> Bi-variate Analysis --> Multi-variate Analysis


<!-- You can include any other section that is pertinent to your problem -->

## General Information
Consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- It is observed that the charged-off rate increases along with the increase in the term
- Suggestion would be to avoid giving long-term loans considering other parameters.
- It is observed that the annual-income is in negative co-relation with the default rate. Lower the 
annual income, better are the chances of default
- It is observed that the default rate increases along with the increase in interest rate.
- It is observed that the default rate is increased when the home ownership is rented

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Numpy
- Seaborn
- Matplotlib