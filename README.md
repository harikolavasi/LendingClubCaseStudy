# Project Name: Lending Club Case Study
Lending Club, a consumer finance marketplace specializing in offering a variety of loans to urban customers, faces a critical challenge in managing its loan approval process. When evaluating loan applications, the company must make sound decisions to minimize financial losses, primarily stemming from loans extended to applicants who are considered "risky."

These financial losses, referred to as credit losses, occur when borrowers fail to repay their loans or default. In simpler terms, borrowers labeled as "charged-off" are the ones responsible for the most significant losses to the company.

The primary objective of this exercise is to assist Lending Club in mitigating credit losses. This challenge arises from two potential scenarios:

Identifying applicants likely to repay their loans is crucial, as they can generate profits for the company through interest payments. Rejecting such applicants would result in a loss of potential business.
On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Background

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **risky** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

## Conclusions

- Major driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. Home ownership of the applicant
  2. Verification Status of the loan application
  3. Loan Status - Dependent column
  4. Purpose of the loan given by applicant
  5. Month on which loan was applied
  6. Number of publicly recorded bankruptcies applied by the applicant
  7. Debt-to-income ratio of the customer
- additional analysis
  8. Loan tenure to loan_status correlation
  9. Loan status and public bankruptcies of the applicant correlation
  10. Loan status and home ownership of the applicant correlation
  11. Loan status and loan amount of the applicant correlation
  12. Loan status and Verification Status of the application correlation
  13. Loan status and interest rates of the loan correlation
  14. Loan status and debt-to-income ratio correlation
  15. Loan status and annul_inc of the applicant correlation
  16. Loan status and purpose of loan correlation



## Technologies Used

- Pandas 
- NumPy 
- Seaborn
- MatplotLib 


## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by @harinatha-r and @harikolavasi - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->