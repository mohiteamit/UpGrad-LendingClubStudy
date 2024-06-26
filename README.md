# UpGrad | EDA | Lending Club Case study
The primary objective of this case study is to understand the factors that influence loan default in the Lending Club dataset. The aim is to identify key factors that indicate if a person is likely to default on their loan, which can help the company make informed decisions to minimize financial losses. Specifically, the company wants to distinguish between borrowers who are likely to repay the loan and those who are at risk of defaulting (labeled as 'charged-off').

## Table of Contents
* [General Info](#general-information)
* [Recommendations](#Recommendations)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
- **This is a student project**.
- Excercise use single notebook and `loan.csv` is data supplied for the excercise.
- Excercise focuses on undertstand what impacts loan default.
- Lending Club loan data set is used for the project though not directly sourced from Lending Club.

## Recommendations

1. **Interest Rate Adjustments:**
   - Implement stricter criteria for loans with higher interest rates due to their strong association with defaults. Adjust the interest rate model to better reflect default risk.
   - A further deep dive is needed to understand if high interest rate justify risker loans

2. **Loan Grade Improvements:**
   - Loand grade is good indictor of default but is not always accurate. Enhance the loan grading system to more accurately capture default risk. Tighten criteria for lower grades and provide incentives for higher-grade loans.

3. **Debt-to-Income Ratio Monitoring:**
   - Closely monitor borrowers with high DTI ratios. Offer financial counseling or debt management support to these borrowers.

4. **Targeted Marketing and Risk Management:**
   - Focus marketing to borrowers with higher incomes and longer credit histories, as these are associated with lower default risk. Develop targeted risk management strategies for lower-income borrowers with shorter credit histories.

5. **Employment Stability:**
   - Incorporate employment length as a significant factor in the loan approval process. Offer loan products tailored to borrowers with stable, long-term employment.

6. **Enhanced Data Collection and Analysis:**
   - Improve data collection methods to capture more granular information on borrower behavior and financial health. Regularly update the analysis to reflect changing trends and patterns in loan defaults.

## Future Investigations:

1. **High Interest Rates and High Risk Loans:**
   - Further deep dive is needed to understand if high rewards from higher interest rates justify the increased risk of defaults.
2. **Deep dive into loan Grade**
   - Current analysis did not explore relationship of `grade` with rest of the parameters. This analysis is needed to make recommendation to better loan application grading

## Technologies Used
- `Python 3`
- `matplotlib` and `seaborn` for plotting
- `scipy.stats` for statistics
- `IsolationForest` from `sklearn` for outlier detection 
- `Visual Studio code` with `Jupyter Notebook` extension 

## Acknowledgements
Neelam Jhunjhunwalla - project partner and UpGrad class mate

## Contact
Created by [@mohiteamit]