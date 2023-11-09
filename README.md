# Lending Club Default Analysis

## Overview
This project analyzes loan data from Lending Club to identify predictors of loan default. The analysis is divided into four main parts: data understanding, data cleaning, data analysis, and recommendations.

## Project Structure
The analysis is organized as follows:

1. **Data Understanding**
   - Loaded the dataset and explored basic information.
   - Identified the target variable as "loan_status."

2. **Data Cleaning**
   - Handled missing values, dropped irrelevant columns.
   - Converted data types for analysis.

3. **Data Analysis**
   - Explored univariate analysis of default rates across various categorical variables.
   - Analyzed loan characteristics, applicant-related information, and loan purposes.
   - Examined default rates across different years and months.
   - Binned continuous variables for a better understanding of default rate variations.

4. **Recommendations**
   - Identified key predictors of loan default.
   - Segmented univariate analysis to compare default rates across different categories.

## How to Use
- The Jupyter Notebook file (`.pynb`) contains the entire analysis.
- Make sure to have the required Python libraries installed (NumPy, Pandas, Matplotlib, Seaborn).
- Execute the cells in the notebook to reproduce the analysis.

## Results
- The project highlights factors influencing loan default rates, providing insights for credit approval decisions.
- Key predictors include grade, term, sub-grade, home ownership, verification status, and purpose of the loan.

## Conclusion
This analysis aims to enhance the credit approval process by leveraging data-driven insights. Understanding the impact of various factors on loan default rates is crucial for making informed lending decisions.

## Future Work
- Consider incorporating machine learning models for predictive analytics.
- Explore additional data sources to enhance the predictive power of the analysis.

## Author
Kartik Soni

Feel free to fork and contribute to the project!

