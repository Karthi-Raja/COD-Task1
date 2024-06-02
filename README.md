# COD-Task1

# Name: Karthik Kumar V
# ID: CT08DS1255
# Domain: Data Science
# Duration: May 25 to June 25
# Mentor: Sravani Gouni
# Description: 

# Objective
This project aims to perform Exploratory Data Analysis (EDA) on a dataset containing data of blood donors distributions, correlations, and outliers through visualizations.

# Key Activities
Data Cleaning: Ensuring the dataset is free from inconsistencies and missing values.
Data Visualization: Creating visualizations to understand data distributions, trends, and relationships.
Correlation Analysis: Identifying correlations between blood donors' data.
Technologies Used
Python: The primary programming language for data analysis.
pandas: Used for data manipulation and analysis.
matplotlib: Employed for creating static, animated, and interactive visualizations.
seaborn: Utilized for making statistical graphics that are informative and attractive.

# Key Insights

Correlations:
The number of donations is strongly correlated with the volume of blood donated by the donor. For each donation, the donor donates 250 cc of blood.
The number of donations made by donors is also positively correlated with the period in months since they first donated. The more time passed since the first donation, the more the number of donations made by the user.
he strongest correlation exists between 'number_of_donations' and 'total_volume_donated_(c.c.)'. This is logical and already expected.
There is a negative correlation between 'months_since_last_donation' and 'made_donation_in_march_2007', indicating that donors who have donated more recently are less likely to donate again in March 2007. This aligns with one of the observations you made from the boxplots.
There is a very weak positive correlation between 'months_since_first_donation' and 'number_of_donations' as well as 'total_volume_donated_(c.c.)'. This may indicate that donors who have been donating blood for a longer time have donated more frequently and/or have donated larger volumes of blood in total.

Risks and Challenges:
The quality of data is a crucial factor that affects the model's performance.
In this project, if the data is not preprocessed and cleaned properly, it may lead to incorrect results.
To mitigate this risk, we have performed data cleaning and preprocessing techniques like removing duplicates and transforming data into normal distribution. We have also performed exploratory data analysis (EDA) to identify the patterns in the data and understand the data distribution.
