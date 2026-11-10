# Bike Sharing
>  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
To model the demand for shared bikes with the available independent variables is required. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* [General Info](#general-information)
* [How to Run](#how-to-run)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
   1. Which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands
- The project models the demand for shared bikes with the available independent variables to be used by the management to understand how exactly the demands vary with different features.
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
- The model was built using numerical and categorical variables with an R2 Score of 78%.
- The numerical variables used in the model are temp and windspeed.
- The categorical variables used in the model are yr,holiday,Spring and Light Rain.
- Thus, the daily demand for bikes depends on whether it is a Holiday, the Season and the Weather. 

## How to run
1. Install the libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn statsmodels
   ```
2. Get the data: day.csv (daily bike demand data; place it next to the notebook).
3. Open and run the notebook:
   ```bash
   jupyter notebook "Bike Sharing.ipynb"
   ```

## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SKLearn
- Statsmodels

