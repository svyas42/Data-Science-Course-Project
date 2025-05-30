# COVID-19 Spread & Vaccination Analysis Using Multiple Linear Regression

-Conducted multiple linear regression to analyze the impact of population and vaccination on COVID-19 spread. Used SQL for data preprocessing and identified key predictors by eliminating insignificant variables. Found a negative correlation between total doses administered and total cases, with active cases being the strongest predictor.

-In this analysis, I aimed to understand how population size and other factors affect the spread and vaccination of COVID-19 across countries. I began by building a multiple linear regression model with TotalCases as the response variable and several explanatory variables, including population, total doses administered, active cases, and vaccination metrics. Initially, I found that some variables (like doses administered per 100 people and percent of the population fully vaccinated) were insignificant, so I refined the model by removing them. This improved the model’s adjusted R-squared value, indicating a better fit.

-I then tested each explanatory variable individually and found that ActiveCases had the highest R-squared value, as expected, since a higher number of active cases correlates with increased total cases. Population and TotalDosesAdministered also showed a significant impact on total cases. Further, the TotalDosesAdministered variable had the lowest p-value in its individual model, confirming its significance in explaining total COVID-19 cases. Through this analysis, I discovered the relationships between population size, vaccination doses, and COVID-19 cases, shedding light on key factors influencing the pandemic's trajectory in various countries

Datasets used: https://www.kaggle.com/datasets/anandhuh/latest-worldwide-vaccine-data
https://www.kaggle.com/datasets/anandhuh/covid19-in-world-countrieslatest-data
