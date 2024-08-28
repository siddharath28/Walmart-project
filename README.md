# Walmart-Sales-Forecasting

![image](https://github.com/DrPoojaAbhijith/Walmart-Sales-Forecasting/assets/160575120/d16d6c9d-e5fe-4398-8822-213b478e5d2e)

## Table Of Contents

1.	Problem Statement
2.	Project Objective
3.	Data Description
4.	Data Pre-processing steps and inspiration
5.	Choosing the algorithm for the project
6.	Motivation and reasons for choosing the algorithm
7.	Assumptions
8.	Model evaluations and techniques
9.	Inferences from the same
10.	Future possibilities of the project
11.	Conclusion
12.	References

## Problem Statement

A retail store that has multiple outlets across the country are facing issues in managing the inventory - to match the demand with respect to supply.
 
## Project Objective

1.	You are provided with the weekly sales data for their various outlets. Use statistical analysis, EDA, outlier analysis, and handle the missing values to come up with various insights that can give them a clear perspective on the following:
a.	If the weekly sales are affected by the unemployment rate, if yes - which stores are suffering the most?
b. 	If the weekly sales show a seasonal trend, when and what could be the reason?
c. 	Does temperature affect the weekly sales in any manner?
d. 	How is the Consumer Price index affecting the weekly sales of various stores?
e. 	Top performing stores according to the historical data.
f. 	The worst performing store, and how significant is the difference between the highest and lowest performing stores.
2.	Use predictive modeling techniques to forecast the sales for each store for the next 12 weeks.
 
## Data Description

Feature Name	  Description
Store	          Store number
Date	          Week of sales
Weekly_Sales	  Sales for the given store in that week
Holiday_Flag	  If it is a holiday week
Temperature	    Temperature on the day of the sale
Fuel_Price	    Cost of the fuel in the region
CPI	            Consumer Price Index
Unemployment	  Unemployment Rate

## Data Pre-processing steps and inspiration

1. Loading the Dataset: The initial step involves loading the dataset into the analysis environment, typically using libraries like Pandas in Python, ensuring accessibility for further examination.

2. Checking for Data Types: It is imperative to inspect the data types of each column to ensure consistency and appropriateness for subsequent analyses and operations.

3. Converting Date Column: When dealing with temporal data, such as dates, converting the date column from an object type to a date type facilitates time-based analyses and visualizations.

4. Handling Outliers: Identification and treatment of outliers are crucial to maintain data integrity. Outliers are assessed visually through plots or statistically using methods like z-scores or IQR (Interquartile Range), ensuring their handling aligns with the context and domain knowledge.

5. Correlation Analysis: Utilizing tools like heatmaps aids in understanding the interrelationships between various features within the dataset, providing insights into potential dependencies and guiding further exploration.

6. Exploring Relationships: Beyond correlation analysis, exploring relationships between columns through visualizations and statistical methods unveils additional patterns and dependencies, enriching the understanding of the dataset's dynamics.

7. Time Series Analysis: Conducting time series analysis involves assessing stationarity through techniques like examining rolling mean and standard deviation, essential for ensuring the reliability of subsequent forecasting models.

8. Forecasting Models Selection: Employing forecasting model ARIMA entails a methodical approach based on the dataset's characteristics and the desired level of complexity, enabling accurate prediction of future trends.

These pre-processing steps and methodologies lay a solid foundation for rigorous data analysis and forecasting, contributing to informed decision-making and actionable insights.
 
## Choosing the algorithm for the project

I am employing ARIMA model to conduct forecast analysis on the provided dataset. These methods offer diverse perspectives for predicting future trends and patterns within the data. ARIMA integrates autoregressive, moving average, and differencing components to capture complex temporal dynamics. By leveraging these techniques, I aim to generate accurate forecasts that inform decision-making and strategic planning. The model facilitates a comprehensive understanding of the dataset's predictive capabilities.

## Conclusion
Based on the analysis conducted on the dataset, it can be concluded that the ARIMA model is the most suitable for forecasting purposes. 

1. Its simplicity and ability to effectively smooth out noise make it particularly well-suited for this dataset.
2. Its straightforward methodology and robust performance make it a reliable choice for generating forecasts.
3. And the model accuracy was also quite good. And its near to 0
4. model accuracy for all the stores is 
Root Mean Squared Error   0.09083478416569807
5. model accuracy for Store 1 
Root Mean Squared Error   0.08634807425384945
6. accuracy for Store 6 
Root Mean Squared Error   0.11624010402978888
7. model accuracy for Store 11 
Root Mean Squared Error   0.10223844724990286
8. model accuracy for Store 17 
Root Mean Squared Error   0.1049818692897262
9. And the model accuracy for Store 33
Root Mean Squared Error   0.07536825631037113

