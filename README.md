# Loan Default Risk Analysis
> Financial services firm Lending Club provides loans to applicants. Customers who do not pay back the loan cause significant loss to the business. The core task is to identify important factors which leads to default of customers. The company will use these factors to for it's portfolio and risk assessment.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Findings](#findings)
* [Recommendations](#recommendations)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- The purpose of this project is to analyze historical loan data to understand the patterns and drivers behind loan defaults.
- This project addresses the business problem of loan defaults, aiming to aid a lending institution in enhancing its risk assessment model.
- The dataset includes 39,000+ loan records from 2007-2011, detailing borrower financial backgrounds, loan characteristics, and repayment statuses.

## Findings
- Loans issued for small businesses have higher default rates, which may be due to variable success rates and financial stability of small businesses.
- Loans with a 60-month term originating in 2010-2011 show higher default rates than those with a 36-month term, likely reflecting economic conditions at the time and the longer financial burden.
- Higher loan amounts correlate with higher default rates, indicating a potential strain on borrower repayment capacity.
- A higher Debt-to-Income (DTI) ratio is associated with higher default rates, suggesting financial over-leverage.
- Lower-income customers exhibit higher default rates, highlighting the challenge in managing loan repayments with limited financial resources.
- Customers with lower credit grades (E, F, G) have higher default rates, reflecting their higher risk profile.
- Higher interest rates are correlated with higher defaults, potentially due to increased borrowing costs.
- Customers residing in Nebraska and Nevada have higher default rates, hinting at regional economic influences.
- No significant correlation was found between default rates and factors such as home ownership or the date of the earliest credit line.

## Recommendations
- Implement additional credit scrutiny measures for small business loans.
- Offer risk-adjusted interest rates for longer-term loans and develop intervention strategies for at-risk borrowers.
- Introduce a graduated risk assessment that increases scrutiny with loan amounts.
- Set stricter DTI cutoffs and provide financial planning resources for high-DTI borrowers.
- Develop specialized loan products with built-in buffers for low-income groups.
- Adjust loan offerings for lower credit grades with higher risk premiums or co-signer requirements.
- Conduct localized risk analysis to tailor lending practices to regional economic conditions.

## Technologies Used
- Pandas - version 1.2.4
- NumPy - version 1.20.2
- Matplotlib - version 3.4.1
- Seaborn - version 0.11.1

## Acknowledgements
- This analysis was conducted as part of an effort to improve the risk assessment process for a lending institution.
- Insights from this project will contribute to the development of more accurate predictive models for loan defaults.

## Contact
Created by [@rajeshraoj] - feel free to contact me!
