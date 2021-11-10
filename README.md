# Loan Lending Club Case Study
Consumer finance company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

## Table of Contents
* Data understanding
* Data cleaning
* Data Analysis
* Recommendations
<!-- You can include any other section that is pertinent to your problem -->

## Data understanding
### Analysis Approach 
• We have to analyze the data to identify the driving factors 
• To start with the data analysis, the data set had to be cleaned and prepared for the analysis, then analyzed and visualized.
• Clean the dataset using appropriate methods 
• Once the data set was cleaned, univariate, bivariate and mulitvariate analysis need to be done
• Visualization techniques were used to draw charts and graphs and then meaningful insights from them 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

### Data Cleaning
• We have analyzed the past loan data for all loans issued through the time period 2007 to 2011.
• Multiple Columns with more than 70% of null values were dropped.
• Missing values were imputed into respective stat, so that all the NULL and NAN values were removed.
• Descriptive columns, other unnecessary columns are removed from the dataset , so that we don’t waste time analyzing those fields

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Analysis
- In our analysis we are interested only in defaulted loans. 
- Default_status column was considered to check how many loans were fully paid and how many were defaulted.
-  Attempted to find total % of defaulted loans
- Two columns are analyzed in Bivariate Analysis to visualize the effect of one value on another. 
- Multiple columns were analyzed against loan_status column to visualize the effect of different parameters on defaulting a loan.
- Bar graphs, Histogram, line graphs were used to visualize the data.
- we performed all the cleaning operations, filtering operations.
-  With cleaned data, we did the following
* Univariate Analysis
* Segmented Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
- After plotting some visualizations, we were able to get some meaningful insights
- (Results are given below)
#### LIBRARIES USED:
- Seaborn & Matplotlib used to visualize 
- Pandas & Numpy were used for analysis.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Recommendations
- After the data clean up and analysis, below are few of the insights that were visualized
1) Around 14% of all the loans get defaulted
2) Higher the loan interest rate, higher the chance of loan getting defaulted
3) Higher the Grade of the Loan ,Higher is the risk of becomingdefaulter.
4) There is higher chance of loan getting defaulted if the loan is taken for the purpose of ‘Small Business’ or ‘Debt Consolidation’
5) Among the verification statuses ,the ‘Verified Status’ Loans have higher Default Ratio when compared to other status defaulter’s ratio
6) Chances of loan default is more if the income of the borrower is less than 25000 and the loan purpose is ‘Other’.
7) Longer the term higher the Defaulters 
8) Dti_Range, defaulter rate increases with increase in dti ratio.
9) Lower Income customers are likely to get defaulted
10) funded_amnt_inv_range wrt purpose , we can observe the similar or upward trend for mostly all the purposes , defaulter ratio increases with increase of loan amount.
11) annual_inc_range wrt purpose , we can observe the similar or downward trend for mostly all the purposes , defaulter ratio is highest for low income ranges
12) interest range wrt purpose , we can observe the upward trend for all the purposes , defaulter ratio increases with increase of interest rate on given loan.
13) installment_range wrt purpose , we can observe the similar or upward trend for mostly all the purposes , defaulter ratio increases with increase of installment amounts of loan.
14) dti_range wrt purpose , we can observe the upward trend for all the purposes , defaulter ratio increases with increase of dti ratio of loan


## Contact
Created by [@praneethkumar4] , Neeraja Kolla - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
