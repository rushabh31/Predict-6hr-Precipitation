# Predict-6hr-Precipitation

This notebook contains code for reading NOAA isd-lite data based on the state or region of interest.

#### Data Preprocessing:
The data was cleaned to eliminate NAs and outliers, and it was normalized so that it could be used in our prediction task.

#### Model Building:
Two distinct models were developed.
1. We used past Precipitation-6hr data to forecast future sequences using this single variable.
2. Using the lstm model, we predicted the Precipitation-6hr sequence using all other variables.

There are accompanying visualizations that show what our models predict.
