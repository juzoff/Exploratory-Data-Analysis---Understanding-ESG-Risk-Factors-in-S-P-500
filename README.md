# Exploratory-Data-Analysis---Understanding-ESG-Risk-Factors-in-S&P-500
This project conducts a comprehensive analysis of Environmental, Social, and Governance (ESG) risk ratings for companies within the S&P 500. It involves importing a dataset containing ESG scores, examining the data structure, and addressing missing values through mean imputation. The project then proceeds with statistical analysis, including ANOVA to investigate the relationship between ESG risk levels and various ESG scores, as well as Chi-Square tests to explore correlations between ESG risk levels and other categorical variables such as controversy levels, sectors, and industries. The results are formatted into a single dataframe for easier interpretation and are ultimately exported to a CSV file for dashboard development via Power BI.

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

![1](https://github.com/user-attachments/assets/48f3f239-29da-473d-a950-d71f7a17f3c1)

5. Chi-Square Tests:
- The project conducts Chi-Square tests to explore the relationships between the categorical variable (ESG Risk Level) and other categorical variables (e.g., Controversy Level, Sector, Industry), calculating statistics like Cramér's V for effect size

![3](https://github.com/user-attachments/assets/32edd6c8-27be-4f50-a256-1ae00d0f91b1)

6. Mean Differences Calculation and Contingency Table Analysis:
- This analysis calculates mean differences in ESG scores across various risk levels and employs a categorical contingency table to examine relationships between ESG risk categories and other categorical variables, enabling deeper insights into patterns and trends within the data

![2](https://github.com/user-attachments/assets/448e6644-4f81-4d38-b6dc-462a9ec77ec0)

![4](https://github.com/user-attachments/assets/059a98e8-2a29-45a1-92e8-2a4c9931380c)

 7. Data Preparation for Export:
- The results from both the ANOVA and Chi-Square tests are formatted and combined into a single dataframe for easier analysis

8. Output:
- Finally, the combined dataframe is exported to a CSV file for PowerBI dashboard development

9. PowerBI Dashboard Development :
- ESG Risk Level Breakdown: The dashboard provides a comprehensive analysis of sectors, industries, and risk scores, showcasing the top 70 sectors and industries by count across all ESG risk levels, along with average Cramer's V and Eta-squared values for categorical and numerical attributes.
- ESG Risk Distribution: It includes a visual representation of ESG risk percentiles and the distribution of risk levels, highlighting how different companies perform across various ESG dimensions.
- Interative Insights: Users can filter data by ESG risk level using a slicer and view aggregated metrics such as the sum of counts and averages for ESG risk levels, helping to identify key trends and patterns.

![Dashboard](https://github.com/user-attachments/assets/24794a65-2d43-4808-b789-a6b75022ed2e)

