# Data Science Projects

1. Yelp SQL Analysis (SQL)

My objective was to perform multiple analyses on a Yelp data set using SQL queries. All queries were executed on SQLite rather than MySQL for this project. The first portion of this project consisted of data profiling and data retrieval. The second portion of this assignment revolved around analyzing patterns and making predictions from the data set. I performed aggregation commands and joined multiple tables together to identify trends in the data.

2. SparkSQL ML Predictions (SQL,Python)

In this project my objective was to use a logistic regression model to predict the `Call_type_Group` in a SQL Table. This project was performed on DataBricks and used Apache Spark clusters. I first had to clean and filter the data so that only relevant data was present. I then converted the SparkDF to pandas to preformat it for sklearn. I then created a pipeline using OHE which I then saved onto the disk. I then finally used the UDF given to me to create a temporary view with the additional column containing the ML predictions.

3. Order+View Binary Testing (SQL)

The goal of this project was to compute binaries for a 30 day window and to compute the lifts in metrics and p-values. This project was performed on mode analytics using postgresql. I used ABBA to find the p-value and to compute the lifts using a 95% confidence interval. This project focused primarily on the use of subqueries and statistical analysis. 

4. GDP Vs Unemployment Over Time (Python,Pandas)

In this project I used pandas to create a dataframe which was used to analyze the GDP agaisnt the unemployment rate over time. This project was done in a Watson Studio from IBM Cloud. The operations of this project revolved around creating and viewing dataframes in python and finally to make a dashboard to visually interpret the data.

5. Covid19VaccinationAnalysis (Python, Pandas, Numpy, Seaborn, Matplotlib, Geopandas)

This was an exploratory data analysis project using a Covid 19 Vaccination dataset on Kaggle (https://www.kaggle.com/gpreda/covid-world-vaccination-progress). Imputed null values and performed multiple analyses such as calculating % change in vaccination rate over time, calculating the 7 day average of daily vaccinations by country, joining the dataset using geopandas to make cholorpleth maps, and finding the correlation between country gdp per capita and percentage of population vaccicnated.

6. Boston Housing Statistical Data Analysis (pandas, seaborn, matplotlib, scipy, statsmodels)

Basic data analysis with a focus on data visualization with the addition of a far more intresting statistical analysis. Performed statistical analyses such as using levene tests to determine equality of variance, T-tests to compare sample means, ANOVA to compare sample means from more than two groups, and using linear regression models (OLS) to make predictions on dependant variables.
