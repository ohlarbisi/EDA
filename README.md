# EDA
Exploratory Data Analysis Lab
In this module you get to work with the cleaned dataset from the previous module.
In this assignment you will perform the task of exploratory data analysis. You will find out the distribution of data, presence of outliers and also determine the correlation between different columns in the dataset.
Objectives
In this lab you will perform the following:
Identify the distribution of data in the dataset.
Identify outliers in the dataset.
Remove outliers from the dataset.
Identify correlation between features in the dataset.
df = pd.read_csv("https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m2_survey_data.csv") 
1.Determine how the data is distributed
The column ConvertedComp contains Salary converted to annual USD salaries using the exchange rate on 2019-02-01.
This assumes 12 working months and 50 working weeks.
Plot the distribution curve for the column ConvertedComp

2.Plot the histogram for the column ConvertedComp.
3. What is the median of the column ConvertedComp?
4. How many responders identified themselves only as a Man?
5. Find out the median ConvertedComp of responders identified themselves only as a Woman?
6. Give the five number summary for the column Age?
7. Plot a histogram of the column Age

Finding outliers
1.	Find out if outliers exist in the column ConvertedComp using a box plot?
2.	Find out the Inter Quartile Range for the column ConvertedComp.
3.	Find out the upper and lower bounds.
4.	Identify how many outliers are there in the ConvertedComp column.
5.	Create a new dataframe by removing the outliers from the ConvertedComp column.

 
