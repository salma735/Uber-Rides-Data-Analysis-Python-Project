# Uber-Rides-Data-Analysis-Python-Project
Project Overview
This project aims to analyze Uber ride data to understand various aspects of ride usage, such as the distribution of rides across different categories, purposes, months, days, and times. The analysis is visualized using a dashboard to provide insights into ride patterns and help make data-driven decisions.
Analysis Steps
Importing Libraries:

Used pandas for data manipulation, numpy for numerical operations, matplotlib.pyplot and seaborn for data visualization.
Loading the Dataset:

Loaded the Uber dataset from a CSV file and displayed the first 10 rows to understand its structure.
Basic Data Exploration:

Generated summary statistics, concise data summary, checked for missing values, duplicate rows, and unique values in each column.
Handling Missing Values:

Filled missing values in the 'PURPOSE' column using forward fill method.
Converting Date Columns:

Converted 'START_DATE' and 'END_DATE' columns to datetime format.
Extracting Date and Time Components:

Extracted date, time, month, and year from 'START_DATE' and 'END_DATE' columns and added these as new columns.
Dropping Original Date Columns:

Dropped 'START_DATE' and 'END_DATE' columns and rearranged the remaining columns.
Handling Missing Values in 'Month' and 'Year' Columns:

Filled missing values in the 'month' and 'year' columns using the mode and converted them to integer type.
Extracting Hour and Minute Components:

Extracted hours and minutes from 'start_time' and 'end_time' columns and added them as new columns.
Calculating Duration:

Calculated the duration of each trip in minutes and added it as a new column.
Plotting Data:

Visualized the data using various plots like heatmap for correlations, count plots, bar plots, and distribution plots to understand the patterns and distributions in the data.

