# Module-11-Assignment - Forecasting Net Prophet

#### by Alex Melino

#

### Overview

This assignment deals with time series analysis, in particlular using a Prophet model to forecast trajectory of popularity for an online marketplace called MercadoLibre. The data used (found in the Resources folder) is of MercadoLibre search trends, daily revenues, and stock prices.

#

### Assignment 

The forecasting_net_prophet.ipynb file contains the python code used for the assignment. In this file, the data is imported, mined, and visualized to identify hourly and seasonal trends. The different sets of data are compared for correlation and to determine if there is a level of predictability based on the data. The final section of the assignment deals with fitting the data to a Prophet() model in order to make predictions 80 days into the future.

This assignment is written for use on GoogleCollab as the first cell of the .ipynb file contains installation of the required libraries. The dependancies and libraries include pandas, hvplot, prophet, holoviews and numpy.

#

### Results

The end results of the analysis show that there does not appear to be any strong correlation between this data in terms of predictability, and the prophet model forecasts a downturn in popularity for MercadoLibre. The analysis also highlighted which times of the day, week, and year are more or less popular for MercadoLibre.
