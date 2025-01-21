# Lending Club Case Study 
Lending Club, a consumer finance marketplace that specialises in providing a variety of loans to urban customers, is facing a significant issue in handling the loan approval process. When analysing loan applications, the corporation must make wise decisions to reduce financial losses, which are primarily caused by loans provided to applicants that are deemed "risky."
These financial losses, known as credit losses, happen when borrowers fail to repay their loans or default. Simply put, "charged-off" creditors are liable for the company's most severe losses.

The major goal of this exercise is to assist Lending Club in reducing credit loss. This challenge stems from two possible scenarios:


- Identifying applicants who are likely to repay their loans is critical since they can produce revenue for the company through interest payments. Rejecting such candidates would mean a loss of potential business.
- On the other side, accepting loans for applicants who are unlikely to repay and are at danger of default can result in significant financial losses to the organisation.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The goal is to identify applicants who are likely to default on loans, resulting in less credit losses. This case study tries to achieve this goal by conducting exploratory data analysis (EDA) on the dataset (loan.csv).

The organisation wishes to identify the underlying causes (or driver variables) of loan default, i.e. the variables that are significant indicators of default. This knowledge can be used by the company to examine its portfolio and risks.

The major goal of this exercise is to assist Lending Club in reducing credit loss. This challenge stems from two possible scenarios:

1. Identifying applicants who are likely to repay their loans is critical, as interest payments can generate revenues for the company. Rejecting such candidates would mean a loss of potential business.
2. On the other side, accepting loans for applicants who are unlikely to repay and are at danger of default can result in significant financial losses to the organisation.

## Conclusions
- Conclusion 1 from the analysis
1) Applicants with grade B have a high chance of Loan Default
2) Applicants with RENT as home ownership have the high chance of Default
3) Applicants with debt consolidation , ie using a new loan to close the existing loans have a high chance of being defaulted
4) Applicants with interest range between 13%-17% have a high chance of being Defaulted
5) Applicants with term 36 months have high chance of being defaulted
6) Applicants with employee length 10 have the high chance of being defaulted
7) Not Verified Applicants have a high chance of becoming Defaulted
8) Loan amount between 4K-8K have the high range of being defaulted
9) Funded_amount_inv in the range of 4K-8K have the high chance of being defaulted
10) Installment in the range if 150-300 have the high chance of being defaulted
11) dti range of 12-15 have the high chance of being defaulted
12) Applicants having a annual_income of range 36k-52K is having high chance of being defaulted
13) Those applicants who have zero inquiry in last 6 months have high chance of being defaulted
14) Applicants having open accounts in the range of 5-10 have the high chance of being defaulted
15) Applicants having Derogatory public records zero have a high chance of being defaulted

- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.14
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by live session of upGrad on EDA by [Abhisheak Saraswat](https://www.linkedin.com/in/abhisheak-saraswat/) and live session of UpGrad on PreCase Study session by [Akashdeep Makkar
](https://www.linkedin.com/in/akashdeep-makkar-12110880/)
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
Created by [Gokul Narayanan](https://github.com/Gokul2448) and [Saurabh Purohit](https://github.com/sp-coding-enthusiast)


