# Prosper Loan Data Analysis  

## Project Overview  
This project presents an exploratory data analysis (EDA) on a dataset sourced from Prosper, a peer-to-peer lending platform. The dataset contains over 113,000 loan records issued between 2005 and 2014, including borrower profiles, loan details, and loan outcomes.

The main goal is to understand how borrower characteristics and loan attributes affect borrowing costs and loan performance. Insights derived from this analysis can inform credit risk assessment and lending decisions.

## Dataset  
- Contains 81 columns and over 100,000 records  
- Includes variables like Borrower APR, Loan Status, Prosper Rating, Income Range, Employment Status, Debt-to-Income Ratio, and more.

## Analysis Summary  
- Borrower APR tends to decrease as Prosper Rating improves (better credit rating → lower interest rates).  
- Borrowers with higher income ranges are more likely to complete their loans successfully.  
- Loan Status and Income Range together strongly influence Borrower APR.  
- Debt-to-Income Ratio correlates with Borrower Rate, reflecting borrower risk.  
- Employment status and loan term also affect loan cost and repayment behavior.

## Methods and Tools  
- Data cleaning and wrangling with pandas  
- Visualizations using matplotlib and seaborn  
- Univariate, bivariate, and multivariate exploratory analysis

## How to Use  
1. Clone the repo  
2. Load the dataset (`prosperLoanData.csv`)  
3. Run the Jupyter Notebook (`EDA_ProsperLoanData.ipynb`) to reproduce the analysis and visualizations

## Conclusion  
This analysis provides valuable insights into the factors influencing loan repayment and borrowing costs, helping to identify risk patterns in peer-to-peer lending.

