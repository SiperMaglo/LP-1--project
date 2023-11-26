 # Analysis of Indian Start-ups Funding (2018-2021)

# Business Understanding

# Objective
The primary objective of this analysis is to understand the dynamics of funding received by Indian start-ups and to uncover insights into the distribution, trends, and correlations among sectors, funding stages, and geographical locations.

# Dataset Overview
The dataset comprises details of various start-ups, their funding amounts, funding stages, sectors, founding years, headquarters, and investors' information. This comprehensive dataset allows us to perform an in-depth analysis of the funding landscape and its implications for different sectors and stages of growth.

# Methodology
We'll employ data visualization techniques, statistical analyses, and exploratory data analysis (EDA) to extract meaningful insights from the dataset. By examining funding trends, sector-wise funding distributions, geographical impact, and stage-specific funding patterns, we aim to provide a comprehensive view of the Indian start-up ecosystem's financial landscape.

## Hypothesis

Null Hypothesis (H0): There is no significant difference in the amount of funding received by different sectors.

Alternative Hypothesis (Ha): There is a significant difference in the amount of funding received by different sectors.

## Research Questions 

1.  Trends in Funding over Time
2.  Which sector receive funding more?
3.  how does the distribution of funding across different stages  relate to the sector's prominence or growth potential?
4.  Which companies received the highest amount of funding?
5.  what are Geographical Distribution of Funding?

## what needed to be done

1. Year of Funding Information:

Display the distribution or counts of funding across different years.
Perhaps create a visual representation like a line chart or a bar chart to show funding trends over the years.

2. Location Information:

Present details about the locations or headquarters of the startups.
Utilize a map or a bar chart to show funding amounts or counts by location.

3. Stage of Development Information:

Showcase the stages at which startups received funding.
Useing a bar chart or pie chart to illustrate the distribution of funding across various stages of development.

4. Sector of Operation Information:

Provideing insights into the sectors in which the startups operate.
Present a pie chart, bar chart, or any visual representation to display the distribution or amounts of funding across different sectors.

5. Amount of Funding Information:

High lighting the funding amounts or ranges received by startups.
Utilize a bar chart, histogram, or other visualizations to represent the distribution of funding amounts.


 Data-Related Issues:

1. Inconsistent Column Names:

Data18's column names differ from other datasets, causing incongruity.
Solution: Rename Data18's column names to align with other datasets.

2. Unnecessary Column:

Data20 includes an unnecessary 'unnamed: 9' column.
Solution: Remove the 'unnamed: 9' column from Data20.

3. Missing Columns in Data18:

Data18 lacks columns for founders, investors, and the year founded.
Solution: Add missing columns with null values for founders, investors, and the year founded in Data18.

4. 'Amount' Column Format:

The 'amount' column in all datasets contains currency symbols, commas, and is stored as a string.
Solution: Convert 'amount' values in all datasets to dollars as floating-point numbers.

5. Null Values:

Null values are present in the 'founded', 'headquarter', 'sector', and 'stage' columns.
Solution: Replace null values in the 'amount' column using the mean or median.

6. 'Headquarter' Column Variations:

Data18's 'headquarter' column contains additional information compared to other datasets.
Solution: Modify Data18's 'headquarter' by separating values with commas and keeping only the first word.

7. Inconsistent 'Sector' Values:

'Sector' values vary among all datasets, making standardization necessary.
Solution: Standardize sector values by merging similar categories (e.g., 'ecommerce' and 'e-commerce platforms' into 'e-commerce').

8. Data Type Inconsistencies:

Most data types are represented as objects, lacking uniformity.
Solution: Adjust the data types of each column accordingly for consistency and accuracy.

## Conclution

Based on our ANOVA Test analysis of the hypothesis, we failed to reject the null hypothesis. This suggests that there isn't a significant difference in funding amounts across various sectors.







