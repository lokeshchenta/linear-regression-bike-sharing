# Prediction of demand for shared bikes
> A US bike-sharing provider wants to understand the factors that influence the demand for shared bikes.
> The company wants to know:
> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- We use Linear Regression to build the model to predict the demand 
- A hybrid approach of both Recursive Feature Elimination(RFE) and manual feature selection is used to select the final set of features/variables for the model.

## Technologies Used
- Python - version 3.11.7
- Pandas - version 2.1.4
- Numpy - version 1.26.4
- Seaborn - version 0.12.2
- Matplotlib - version 3.8.0
- Jupyter Notebook - version 7.0.8
- statsmodels - version 0.14.0
- scikit-learn - version 1.2.2

## Conclusions
- The variables temp, year, weathersit(value=3 light rain), spring season are big factors influencing the demand of shared bikes.
- Temperature and Year have positive effect/relation on the demand for bikes.
- Light rain and spring season have a negative effect on the demand.

## Acknowledgements
This project is done as part of the IIIT Bangalore Executive PG Programme in Machine Learning & AI.
