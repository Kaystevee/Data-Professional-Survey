# Data Professional Survey

# Introduction
The data survey profession project aims to analyze demographics and sentiments within the data profession. This documentation focuses on the data-cleaning steps undertaken to ensure the quality and reliability of the dataset.

# Objectives
The primary objective of the data cleaning project is to prepare a clean and reliable dataset for subsequent analysis. Clean data is crucial for obtaining accurate insights into the demographics and sentiments of professionals in the data survey.

# Source
[Alex the Analyst](https://youtu.be/pixlHHe_lNQ?si=DfS4Po51BdKNkLNB)

# Dataset Overview
**The dataset consists of the following columns:**
* Unique ID
* Email
* Date Taken (America/New_York)
* Time Taken (America/New_York)
* Browser
* OS
* City
* Country
* Referrer
* Time Spent
* Q1 - Which Title Best Fits Your Current Role?
* Q2 - Did you switch careers into Data?
* Q3 - Current Yearly Salary (in USD)
* Q4 - What Industry do you work in?
* Q5 - Favorite Programming Language
* Q6 - How Happy are you in your Current Position with the following? (Salary)
* Q6 - How Happy are you in your Current Position with the following? (Work/Life Balance)
* Q6 - How Happy are you in your Current Position with the following? (Coworkers)
* Q6 - How Happy are you in your Current Position with the following? (Management)
* Q6 - How Happy are you in your Current Position with the following? (Upward Mobility)
* Q6 - How Happy are you in your Current Position with the following? (Learning New Things)
* Q7 - How difficult was it for you to break into Data?
* Q8 - If you were to look for a new job today, what would be the most important thing to you?
* Q9 - Male/Female?
* Q10 - Current Age
* Q11 - Which Country do you live in?
* Q12 - Highest Level of Education
* Q13 - Ethnicity

# Tools Used
* MS Excel
* Power BI

# Data Cleaning Process
**Data import**
* Downloaded the dataset, had an overview of the CSV file on Excel, and imported the Dataset to Power BI
**Data cleaning**
* Deleted empty  and non-used columns.
**Create Desired demographics** 
* in column (Which Title Best Fits Your Current Role) 'Split column' 'By Delimiter' using 'Custom' '(' 'split at' 'left-most Delimiter' 'OK'. This is done so as to create a separate column  to have the  desired demographics, And then delete the new column.
* Repeat the previous step in column (What Industry do you work in) 
* Repeat the previous step in column (Which Country do you live in)
* Repeat the previous step in column (Favorite Programming Language) but using 'colon' split at 'left-most Delimiter
* Make a new column to calculate the Average salary using (Current Yearly Salary (in USD))
* 


