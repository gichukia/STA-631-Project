# STA-631-Project
Comparing Multiple Linear Regression model and Decision Tree Regressor



This project entails comparing  Multiple Linear Regression and Decision Tree Regressor using Formular One (F1) data. The project involves first selecting desired variables to predict "Fastest Lap Speed" for a F1 race, then fitting different multiple linear regregression on the data using the variables to obtain the best model that explains the most variability in "Fastest Lap Speed". The final model from the multiple linear regression (MLR) analysis shows the best model entails predicting “fastestLapSpeed” using six variables: “points”, “lap”, “altitude”, “fastestLapDuration”, “averagePitstopDuration” and “averageLapDuration”. I then use the variables from the decired MLR to predict "Fastest Lap Speed" using a Decision Tree Regressor and compare the performances for both. 
The data use was obtained from tidytuesday, https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-09-07/readme.md, and was cleaned u9sing R to obtain a set of variables and a data set that was used for the analysis. The cleaning script and clean data set is attahed to this repository.
