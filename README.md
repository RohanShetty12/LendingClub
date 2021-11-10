# Lending Club Case study
> This is an Exploratory Data Analysis project on the Lending Club Case study. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Recommendations](#Recommendations)


## General Information
### Introduction
We have a company which is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

### Business Objective
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (Credit Loss) i.e borrowers who default cause the largest amount of loss to the lenders. The company wants to understand the driving factors behind loan default so that they can evaluate these parameters in the loan application and effectively decide if they can Approve or Reject loan

### Problem Statement
Whenever the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

We need to analyze the dataset provided by the company and perform an Exploratory Data Analysis to highlight the list of driving factors which influence the possibility of an applicant repay the loan or defaulting on it.


## Recommendations
After analyzing the above findings, i have listed down a consolidated list of suggestions which would help the organization in approving good loans and rejecting the bad loans:
- The probability of a loan defaulting would drastically reduce if we **reduce the interest rates**. Its been observed that higher interest rates combined with longer loan tenure would result in higher interest amount to paid as compared to the prinicpal amount. This would eventually result in the borrower not being able to keep up with the obligation and hence defaulting.
- Extending point 1, **longer tenure period should be discouraged**, specifically for candidates who have higher interest rate or lower grade. Its observed that longer the tenure higher the probability of loan default.
- The company should **reconsider approving loan for candidates who have a lower grade** i.e C, D or E
- If the candidate, in the recent times, had **made multiple inquiries ,then such applications should be scrutinized**. 
- Loan applications from candidates who **tend to utilize their credit to the limit should be re-considered**.
- **Higher income candidates should be given preference in approving loans**, as its observed that higher income candidates tend repay their loans when compared with lower income candidates.



## Technologies Used
- numpy - 1.16.2
- pandas - 0.24.2
- matplotlib - 3.0.3
- seaborn - 0.11.2

## Contact
Created by [@RohanShetty12] - feel free to contact me!