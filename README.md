# SEATLE-HOUSE-PRICE-PREDICTION
This project covers the prediction of Seattle, Washing, USA  house prices using Ridge, RidgeCV Lasso and LassoCV regularization models.
Once extreme outliers were removed and the data cleaned, a straightforward regularized linear model was able to explain roughly 64–65 % of the variance in house prices and reduce prediction error by a solid 40 % relative to the naïve baseline. The very small differences among the four regularized models suggest that, for this particular dataset, the choice between Ridge and Lasso (or between manual tuning and cross-validated tuning) matters less than simply applying sensible regularization.

## DATASET
The dataset used is a real dataset of house prices sold in Seattle, Washington, USA between August and December 2022.   Prediction of the house price in this area was based on several features, which are described below.

## Features

 Feature  -        Description                                                                 

 beds      -       Number of bedrooms in the property                                          
 baths    -        Number of bathrooms in the property. Note: 0.5 corresponds to a half-bath                      (sink and toilet only, no tub or shower) 
 
 size        -     Total floor area of the property                                            
 size_units   -    Units of the previous measurement                                             
lot_size-Total area of the land where the house is located. The lot belongs to the house owner 
 lot_size_units -  Units of the previous measurement                                          
zip_code        - Zip code (postal code used in the USA)                                        
 price          - Price the property was sold for (US dollars)                                

## Useful Fact
 1 acre = 43,560 sqft


#3 DATA SOURCE:
 The dataset used in this project is HOUSE PRICE PREDICTION-SEATTLE, published by Samuel Cortinhas on kaggle
 
 Dataset-HOUSE PRICE PREDICTION-SEATTLE
 Platform-Kaggle
 Year-2022
 Source: https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle/data
