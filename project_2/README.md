My final assignment during my contract period as a Data Scientist virtual internship at [Id/x Partners](https://idxpartners.com/), the dataset provided contained projects from lending companies and was asked to build a model that can predict Credit Risk consisting of data on loans accepted and rejected.
<br>
First I want to say thank you to [Rakamin](https://www.rakamin.com/virtual-internship-experience) who has become a liaison.

# Credit Risk
A [credit risk](https://en.wikipedia.org/wiki/Credit_risk) is risk of default on a debt that may arise from a borrower failing to make required payments. In the first resort, the risk is that of the lender and includes lost principal and interest, disruption to cash flows, and increased collection costs. The loss may be complete or partial. In an efficient market, higher levels of credit risk will be associated with higher borrowing costs. Because of this, measures of borrowing costs such as yield spreads can be used to infer credit risk levels based on assessments by market participants.

# Code Used
**Python Version :** 3.9.7
<br>
**Packages :** pandas, numpy, missingno, seaborn,matplotlib.pyplot, plotly.express, sklearn.

## Table of Content
- Current Problem
- Major Goal
- The Findings

# What is The Current Problem?
Some customers have the risk of default which results in losses for the lender.

# Our 2 Major Goals
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/2%20major%20goals.png)

# Our Solution to Solve Current Problem
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/flowchart.png)

# Exploratary Data Analysis
In this data, loan categories are divided into 7 grades, namely A, B, C, D, E, F, G and each grade has 5 levels.
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/state.html)
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/Grade%20vs%20Loan_amnt.png)

![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/grade%20and%20emp%20vs%20status.png)
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/Installment%20%26%20annual_inc%20vs%20grade.png)
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/int%20vs%20grade.png)
![](https://github.com/Anggytriputra/Anggy_Portofolio/blob/main/project_2/images/density%20plot.png)

# Summary EDA
1. We can see from the picture above that with each grade level increases, the loan amount increases.
2. The higher the grade level, the higher the risk of loan default.
3. Employment length in years does not affect the risk of loan default.
4. The higher the grade level, the lower the average yearly income of the borrower and who are at risk of default on loans with annual income < $45,000.
5. In the previous statement, that the higher the grade, the higher the loan amount and make the monthly installments bigger to repay the loan, and we can see in the density plot that monthly installments > $ 280 have a risk of default.


# Modelling
