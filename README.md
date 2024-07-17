# Women-E-Commerce-Clothing-Reviews-EDA
This repository contains a comprehensive exploratory data analysis (EDA) of the Women's E-Commerce Clothing Reviews dataset. The analysis aims to uncover insights into customer reviews, including the distribution of recommendations, clothing categories, and key statistics.

#Dataset Overview
The dataset includes various features related to women's clothing reviews, such as:
Division Name: The division of the clothing item.
Department Name: The department in which the item is categorized.
Class Name: The specific class of clothing.
Clothing ID: Unique identifier for each clothing item.
Recommended IND: Indicates whether the item was recommended (1) or not recommended (0).

#Key Steps in the Analysis

Data Loading and Overview: The dataset is loaded using Pandas, and basic exploratory commands are executed to understand its structure, including the number of missing values and unique values for each column.

Data Cleaning: Unnecessary columns are dropped, and missing values are assessed.
Categorization of Data: Numerical and categorical features are identified for further analysis.

Visualization:
Pair plots to examine relationships between features colored by recommendation status.
Pie charts to visualize the distribution of recommendations.
Count plots for categorical variables to show distribution across different categories.
A count plot for the top 50 clothing IDs.

#Requirements
To run this analysis, you will need the following Python libraries:

pandas
numpy
matplotlib
seaborn

