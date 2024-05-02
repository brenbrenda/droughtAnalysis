
# Drought anaylsis in US

## Descrtiption
this code uses various machine learning models from 
https://github.com/khushpanchal/Drought_Prediction/blob/master/ASCE_MeteorologicalDroughtQuantification.pdf
this thesis
while the difference is the duration is implemented 24 years which is diffrent fromthe report of 70 years.
## Usage 
the notebook does the following:
1. loads historical data from two locations Misssisipi and Albeny
2. Fits the models of LSTM and ARIMA on the traing data
3. Generate rainfall forecast 

## data collection
from monthly rainfall data from 2000-2024 forecast future rainfall using models.
from the website



## Repository Structure
.
├── Albeny.csv                    # reformatted data for Albeny (monthly)
├── rainfull_Albeny.csv           # historical rainfall data for Albeny(daily)  
├── Mississippi.csv               # reformatted data for Mississippi (monthly)
├── rainfull_Mississippi.csv      # historical rainfall data for Mississippi(daily)
├── Mississippi and Albeny.ipynb # main notebook to generate forecasts
├── environment.yml          # conda environment specification
└── README.md






