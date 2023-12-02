# Churn Analysis

## Problem Statement

A churn analysis is a method used by banks to predict which customers are likely to leave or unsubscribe from their services. The analysis aims to answer two main questions: which customers are churning? and why are they churning?



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset are one csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Use "conditional column" to add age group, credit score group and balance columns.
- Step 4 : Use "index column" to arrange these groups into correct order. Check their relationship at model view.
- Step 5 : Use measures to calculate no. of customers, no. of lost customers and churn rate.
- Step 6 : Add "Min. churn rate", "Max. churn rate" and "Target churn rate" columns for gauge chart.
- Step 7 : Use line and bar charts to represent the relationship between customer age groups, credit score groups, account balance and their respectiev churn rates.
- Step 8 : Add new button slicer for "churned" and "not churned" customer groups.
- Step 9: Enhance the report using theme.

### Analysis 

Based on the observation, the average churn rate is 20.4%, which is higher than the target of 15%. The churn rate is highest in the 51-60 age group. The churn rate is higher for customers with a credit score below 500 but remains steady as the credit score increases. The churn rate peaks at an account balance of 1k -10k, decreases as the account balance increases but rises again for high net worth - over 200k.

The high churn rate in the 51-60 age group could be due to the fact that this group is more likely to be retired or approaching retirement. They may be looking to reduce their expenses and may not see the value in the product or service.

The higher churn rate for customers with a credit score below 500 could be due to the fact that they may be struggling financially. They may be looking to reduce their expenses and may not see the value in the product or service.

The peak in churn rate at an account balance of 1k -10k could be due to the fact that customers in this range may be more likely to be living paycheck to paycheck. They may be looking to reduce their expenses and may not see the value in the product or service.

The rise in churn rate again for high net worth customers over 200k could be due to the fact that they may have more options available to them. They may be looking for a more personalized service or may be looking for a product or service that is more tailored to their needs.
