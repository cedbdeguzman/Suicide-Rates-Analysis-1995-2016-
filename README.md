# Suicide Rate Analysis (1995-2016)
  
## Project Overview
This is a data analysis project for the Suicide Rate Trend from 1995 to 2016 using Python.


## Author
* [cedbdeguzman](https://github.com/cedbdeguzman)

## Table of Contents
* [Methods](#Methods)
* [Data Cleaning Process](#Data-Cleaning-Process)
* [Exploratory Data Analysis](#Exploratory-Data-Analysis)
* [Overview of the Results](#Overview-of-the-Results)
* [Insights](#Insights)

## Data Source
* The CSV file was downloaded from the Kaggle website.

  
## Tools 
* Python - Data Cleaning/Exploratory Data Analysis/Data Visualization

  
## Methods
In this project, the Python Jupiter Notebook was used for all the Data Analysis process, starting from loading the CSV dataset file up until the Data Visualization. Matplotlib and Seaborn libraries were used for Data Visualization.

### First Phase 
 In the initial phase of data preparation, the following tasks were performed: 

 1. Load the CSV file using pd.read_csv().
 3. Removed duplicate rows, change the format of column names, detecting and replacing outliers and filling missing values.
 4. Check if each column has correct data types.

### Second Phase
 EDA involves exploring the sales data to answer some of the following questions:

 1. What year has the most number of suicides? 
 2. Which gender has the most suicide cases?
 3. Which country has the highest suicide cases?
 4. Is there a relationship between the measure of standard of living like HDI and GDP to a person commiting a suicide?

### Last Phase
  For each question, the necessary python syntax like group by, sorting, and other aggregation methods were used to come up with a table to make an inference. Matplotlib and Seaborn
  libraries were then used to graph the data.

## Data_Cleaning_Process 
Notebook file for Data Cleaning is uploaded in the repository section. 

Steps: 

1. Load the CSV file using pd.read_csv()
2. Remove unecessary characters on column title and capitalize each word.
3. Repeat step 2 for each category columns.
4. Select necessary columns for analysis.
5. Drop duplicate rows
6. Detect outliers by graphing each numeric column using boxplot.
7. If the graph is skewed distribution and has potential outliers, use inter quartile rule for removing outliers.
8. If the graph is symmetric distribution, use standard deviation rule for removing outliers.
9. If the outliers are valid values for each column, just retain them.
10. If the count of outliers are almost 10% of the total values on that column, retain them. Removing the outliers or replacing them can affect the accuracy of the result since 10% is significant.
11. Detect null values and replace them with zero or median value.
12. If the numeric column has null values with extreme outliers, use the median value as a replacement for null values instead of mean value since it can be affected due to presence of extreme outliers.
13. Check if each columns has correct data types.

## Exploratory Data Analysis
See the notebook file for EDA process

## Overview of the Results



## Insights

From 1985 to 2016, there is a decrease in trend of the suicide cases. The highest suicide cases was on 1999. For suicide number per 100k population, year 1995 has the highest ratio. Russian Federation was the country with the highest suicide cases recorded. Male gender with age bracket of 35-54 years was its dominant charateristics. There was no relationship among HDI, GDP, GDP Per Capita, and Suicide Number; meaning the measure of standard of living of a country has nothing to do with the person commiting a suicide. 
