# Project : Cost of Living Analysis

# Project overview:

# Objective
The objective of this project is to analyze global trends in cost of living and average monthly income across multiple countries and regions. By performing Exploratory Data Analysis (EDA), we aim to understand the relationship between the income level of individuals and the expenses required to maintain living standards in different parts of the world. Through data visualization and statistical interpretation, this project highlights economic differences between regions, identifies patterns of affordability, and provides insights that may assist individuals, policymakers, and businesses in making informed decisions regarding relocation, salary benchmarking, and international market evaluation.
# Dataset Description
This dataset provides economic indicators related to household income and cost of living across countries. It contains 201 rows  and 5 columns. Each row represents a country at a specific point in time.The dataset includes both financial and regional information, allowing for meaningful comparison across different geographic and economic groups.The data originates from classroom-provided datasets compiled from Numbeo and public economic databases.
# Key Variables:
• Country : The name of the country where the data was recorded.

• Region : The geographical region to which the country belongs

• Year : The year when the data was recorded.

• Average_Monthly_Income : The average monthly income of individuals in USD.

• Cost_of_Living: The average monthly cost of living in USD, including essentials like housing, food, and utilities.

# Data Cleaning:

# Missing Values
Analyzing the dataset revealed missing values in the Average_Monthly_Income and Region columns. To address this, the median imputation method was applied for numerical data and the mode was used for categorical data, ensuring accuracy while maintaining data consistency. After processing, the dataset is complete and ready for further analysis.
# Duplicated Values
The dataset check revealed 2 duplicate records. These duplicates were removed to avoid repetition and maintain data accuracy. After cleaning, the dataset contains 199 unique rows, ensuring reliable and consistent information for analysis.
# Outliers
The boxplot results indicate that there are no significant outliers in the variables Year, Average Monthly Income, and Cost of Living. All data points fall within reasonable ranges, with no values exceeding the boxplot limits. This shows that the dataset is stable, consistent, and suitable for further analysis.
<img width="1432" height="470" alt="image" src="https://github.com/user-attachments/assets/86cfe452-b424-4cca-b438-3e64228052db" />
# Descriptive Statistics
<img width="533" height="299" alt="image" src="https://github.com/user-attachments/assets/57c7272e-738f-41ad-bb2f-484daf944150" />

The dataset provides descriptive statistics for three key variables: Year, Average Monthly Income, and Cost of Living. The data spans from 2000 to 2023, with an average year of 2011. Average Monthly Income has a mean of 4,274, ranging from 535 to 7,976, while the Cost of Living has a mean of 3,700, ranging from 484 to 7,081. Both variables show relatively high standard deviations (2,129 for income and 1,985 for cost of living), indicating considerable variation across observations. These results suggest differences in income levels and living expenses over time, reflecting possible economic disparities between years or regions.

# Analysis Findings:
<img width="793" height="464" alt="image" src="https://github.com/user-attachments/assets/74f111e4-f661-4495-8902-f2412b0f2ec4" />

Figure 1. Average Income Changes Over Time (2000–2023).
The analysis below provides deeper insights into these observed trends and their potential implications:

• The line chart illustrates notable fluctuations in average monthly income from 2000 to 2023, revealing several cycles of growth and decline. There is a clear upward movement around 2010, followed by varying income levels across subsequent years, reflecting periods of economic recovery and contraction. The sharp rise near the end of the period suggests a short-term boost in earnings, which may be linked to inflationary pressures or shifts in global market dynamics.

• Overall, the pattern demonstrates that income trends are not stable over time but are highly influenced by broader economic conditions and external shocks. These findings emphasize the importance of economic resilience, consistent job creation, and sustainable wage policies to maintain steady income growth amid changing global circumstances.


<img width="836" height="464" alt="image" src="https://github.com/user-attachments/assets/e866e2d5-70be-4ddd-9474-46dd3fff8104" />

Figure 2. Income vs Cost of Living. 
The following analysis explores this correlation in greater depth to uncover its economic implications:
• The scatter plot presents the relationship between average monthly income and cost of living, revealing a generally positive association between the two variables. As income levels rise, the cost of living also tends to increase, suggesting that higher-earning regions often face greater expenses. This pattern aligns with the concept of economic parity, where regions with stronger economies and higher wages also experience elevated consumer prices and living standards.

• The dispersion of data points indicates variability across different observations, meaning that some regions may achieve higher income levels without a proportionate rise in living costs, while others struggle with high expenses despite moderate income. This finding highlights the importance of balanced economic growth—ensuring that wage increases keep pace with inflation and living expenses to maintain sustainable purchasing power and overall financial stability.






