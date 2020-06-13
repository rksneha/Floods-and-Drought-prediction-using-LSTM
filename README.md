# Floods-and-Drought-prediction-using-LSTM
A deep learning project that predicts chennai's rainfall sequence for a time series and analyses current condtion as normal or flood or drought.

## ABOUT:
Predicting a future condition has always been a great boon with ML techniques. But, most of ML models fail to understand/memorise the longer dependencies.
The use of Deep Learning techniques for the same has helped through to eradicate this issue. In a case to predict next day's rainfall, just a previous day's 
weather conditions is not sufficient. We require atleast a 15 days conditions to analyse today's weather conditions. In such situations to remember longer dependencies,
LSTM model works very efficiently. <b>An LSTM model</b> can understand longer depndencies through its memory and reset cell structures. I have used this to predict amount of rainfall we can expect for next day for upto a long sequence of 2 years.
With the predicted rainfall for next day, analysis for flood or drought or normal conditions has been done through analysing the percent of rainfall received as compared to average expected for a place in a particular month.
A dataset of 12 columns with 8 notifying present atmospheric conditions and four about chennai's water level has been used to train the model.

## DATASET
The day-wise dataset for this project has been downloaded from NASA’s Global Modelling and Assimilation Office Online.  It contains a total of ​12 columns​ and has about 4 years of daily conditions as data rows.  
 It contains the following weather related fields- ​Rainfall​, ​Relative Humidity​, ​Pressure​, Wind Speed​, ​Wind Direction​, ​Snowfall​, ​Snow-depth ​and ​Short wave irradiation (Sunlight). 
 The columns Snow fall and snow depth has been removed. The chennai's 4 reservoirs' water levels that has been taken from kaggle has been merged with this dataset since the rows can be identified with dates.
 
 
