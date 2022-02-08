# Lending Club Case Study
> This case study harnesses Exploratory data analysis to find out which loan applicants will default.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Proposals and Recommendations](#proposals-and-recommendations)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company:
- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
    - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Following variables drive the defaulter rate.
- **Loan Amount**: With increase in loan amount the defaulting rate increases.
- **Interest Rate**: With the increase in interest rate, defaulting rate also increases.
- **Annual Income**: Defaulting rate increases with lower annual income.
- **DTI**: With higher DTI, the defaulting rate increases.
- **Grade**: Defaulting rate increases as we move from grade ‘A’ to grade ‘G’.
- **Revolving rate of utilization**: With increase in the revolving line of utilization, the defaulting rate increases

## Proposals and Recommendations
1. Sanction loans of small amounts
2. Extremely high interest rates must be avoided
3. Decrease loans for applicants with low annual income
4. Approve loans for applicants with lower debt
5. Consider loaning often to grades A, B, C over F, G
6. Decrease loaning to applicants with high revolving line of utilization



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Numpy
- Pandas
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@saurabhdugdhe](https://github.com/saurabhdugdhe)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
