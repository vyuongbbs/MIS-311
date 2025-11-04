# Project : Cost of Living Analysis
# Project overview 
# Objective 
The objective of this project is to analyze global trends in cost of living and average monthly income across multiple countries and regions. By performing Exploratory Data Analysis (EDA), we aim to understand the relationship between the income level of individuals and the expenses required to maintain living standards in different parts of the world. Through data visualization and statistical interpretation, this project highlights economic differences between regions, identifies patterns of affordability, and provides insights that may assist individuals, policymakers, and businesses in making informed decisions regarding relocation, salary benchmarking, and international market evaluation
# Dataset Description
This dataset provides economic indicators related to household income and cost of living across countries. It contains 201 rows  and 5 columns. Each row represents a country at a specific point in time.The dataset includes both financial and regional information, allowing for meaningful comparison across different geographic and economic groups.The data originates from classroom-provided datasets compiled from Numbeo and public economic databases.
# Key Variables:
• Country : The name of the country where the data was recorded.
• Region : The geographical region to which the country belongs
• Year : The year when the data was recorded.
• Average_Monthly_Income : The average monthly income of individuals in USD.
• Cost_of_Living: The average monthly cost of living in USD, including essentials like housing, food, and utilities.
# Data Cleaning
# Missing Values
Analyzing the dataset revealed missing values in the Average_Monthly_Income and Region columns. To address this, the median imputation method was applied for numerical data and the mode was used for categorical data, ensuring accuracy while maintaining data consistency. After processing, the dataset is complete and ready for further analysis.
# Duplicated Values
The dataset check revealed 2 duplicate records. These duplicates were removed to avoid repetition and maintain data accuracy. After cleaning, the dataset contains 199 unique rows, ensuring reliable and consistent information for analysis.
# Outliers
The boxplot results indicate that there are no significant outliers in the variables Year, Average Monthly Income, and Cost of Living. All data points fall within reasonable ranges, with no values exceeding the boxplot limits. This shows that the dataset is stable, consistent, and suitable for further analysis.
<img width="1432" height="470" alt="image" src="https://github.com/user-attachments/assets/86cfe452-b424-4cca-b438-3e64228052db" />



