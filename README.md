# Linear Regression Assignment

## Table of Contents
* [Problem Statement](#problemstatement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Problem Statement
### Introduction
Solving this assignment will give you an idea about how real business problems are solved using linear regression. 
### Business Understanding
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
The company is finding it very difficult to sustain in the current market scenario. 
So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

### Results Expected

1. Write all your code in one well-commented Python file; briefly mention the insights and observations from the analysis 
    - Present the overall approach of the analysis in a presentation: 
    - Mention the problem statement and the analysis approach briefly 
    - Explain the results of multi leanier regression 
2. Include visualisations and summarise the most important results 


## Conclusions
The multiple linear regression model built to predict bike rentals (`cnt`) based on various features such as temperature, season, year, and weather conditions has shown a good performance with an R-squared score of approximately 0.85. This indicates that the model explains about 85% of the variance in the bike rental counts.

Key observations:
1. High Correlation Features: The features `atemp` (feels-like temperature), `temp` (actual temperature), and `yr_2019` (year 2019) have shown significant contributions towards predicting bike rentals.
2. Seasonality and Weather: The analysis indicates that bike rentals vary significantly across different seasons and weather conditions, with clear weather and warmer temperatures leading to higher rental counts.
3. Residual Analysis: The residuals are fairly normally distributed, and the residuals vs. predicted values plot does not show any obvious patterns, suggesting that the model's assumptions are reasonably met.

Overall, the model provides a reliable prediction of bike rentals based on the given features, and it can be used by the real estate company to optimize their strategies for bike-sharing systems.

## Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
