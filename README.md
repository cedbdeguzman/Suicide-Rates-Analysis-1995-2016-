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

## Data Cleaning Process 
Notebook file for Data Cleaning is uploaded in the repository section. 

Steps: 

1. Load the CSV file using pd.read_csv().
2. Remove unecessary characters on column title and capitalize each word.
3. Repeat step 2 for each category columns.
4. Select necessary columns for analysis.
5. Drop duplicate rows.
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
![Image](https://github.com/user-attachments/assets/cae318e6-4558-4c3b-819c-1eb481d3efc7)
![Image](https://github.com/user-attachments/assets/becf0c93-96a4-4a93-a838-b49643e599fd)
![Image](https://github.com/user-attachments/assets/dc8d11a9-43ad-4b85-9607-6e59792b6f01)
![Image](https://github.com/user-attachments/assets/da3ca55f-6f21-4a30-8814-d3642bf34442)
![Image](https://github.com/user-attachments/assets/ddb2ca4c-38ff-477a-89df-21d0d31ac755)
![Image](https://github.com/user-attachments/assets/eb297ae3-9d7e-4e4d-ba27-57cc8fde7434)
![Image](https://github.com/user-attachments/assets/a498716a-9af7-4d5e-a310-d9546a8cc96c)
![Image](https://github.com/user-attachments/assets/09195771-d0b9-4fd1-88dc-e0ace81a3ee8)
![Image](https://github.com/user-attachments/assets/8e4164ae-9606-4c70-84b1-d30adfda2b14)
![Image](https://github.com/user-attachments/assets/e0f14b1e-8cff-4863-8d7d-ce9ca5fd3803)
![Image](https://github.com/user-attachments/assets/deba520b-0cc4-4561-90b2-0a9f0136b132)
![Image](https://github.com/user-attachments/assets/ae14264c-dc7f-450a-9604-20727fcd6629)
![Image](https://github.com/user-attachments/assets/d1eac195-1f88-40e2-9c98-9e1f194f34f9)
![Image](https://github.com/user-attachments/assets/ad2030c0-3619-499b-a50f-f858d1c91708)


## Insights

From 1985 to 2016, there is a decrease in trend of the suicide cases. The highest suicide cases was on 1999. For suicide number per 100k population, year 1995 has the highest ratio. Russian Federation was the country with the highest suicide cases recorded. Male gender with age bracket of 35-54 years was its dominant charateristics. There was no relationship among HDI, GDP, GDP Per Capita, and Suicide Number; meaning the measure of standard of living of a country has nothing to do with the person commiting a suicide. 
