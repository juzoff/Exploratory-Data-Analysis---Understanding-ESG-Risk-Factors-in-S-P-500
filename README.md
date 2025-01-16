# Exploratory-Data-Analysis---Understanding-ESG-Risk-Factors-in-S&P-500
This project analyzes ESG risk ratings for S&P 500 companies, addressing missing values, performing ANOVA for ESG score relationships, and using Chi-Square tests for correlations with categorical variables. Results are formatted and exported for Power BI dashboard development.

## Components: 

1. Data Import and Preview:
- The project loads a dataset containing ESG risk ratings and displays the first few rows to get a sense of the data structure

2. Data Structure Examination: 
- The data structure is inspected to understand the data types and the presence of any missing values

3. Missing Value Handling: 
- The code checks for missing values and replaces them with the mean for certain numeric columns (Environment, Governance, Social Risk Scores, and Total ESG Risk Score)
- It also checks for empty strings in the ESG Risk Level column and removes those rows

4. ANOVA Analysis:
- The project performs ANOVA (Analysis of Variance) to analyze the impact of the categorical variable (ESG Risk Level) on several numeric variables (different ESG risk scores) and calculates the p-values and effect sizes (eta-squared) from these analyses

5. Chi-Square Tests:
- The project conducts Chi-Square tests to explore the relationships between the categorical variable (ESG Risk Level) and other categorical variables (e.g., Controversy Level, Sector, Industry), calculating statistics like Cramér's V for effect size

6. Mean Differences Calculation and Contingency Table Analysis:
- This analysis calculates mean differences in ESG scores across various risk levels and employs a categorical contingency table to examine relationships between ESG risk categories and other categorical variables, enabling deeper insights into patterns and trends within the data

 7. Data Preparation for Export:
- The results from both the ANOVA and Chi-Square tests are formatted and combined into a single dataframe for easier analysis

8. Output:
- Finally, the combined dataframe is exported to a CSV file for PowerBI dashboard development

9. PowerBI Dashboard Development :
- F
