# STA-631-Project
### Comparing Multiple Linear Regression model and Decision Tree Regressorn using Formula One Data



This project entails comparing  Multiple Linear Regression and Decision Tree Regressor using Formular One (F1) data. The project involves first selecting desired variables to predict "Fastest Lap Speed" for a F1 race, then fitting different multiple linear regregression on the data using the variables to obtain the best model that explains the most variability in "Fastest Lap Speed". The final model from the multiple linear regression (MLR) analysis shows the best model entails predicting “fastestLapSpeed” using six variables: “points”, “lap”, “altitude”, “fastestLapDuration”, “averagePitstopDuration” and “averageLapDuration”. I then use the variables from the decired MLR to predict "Fastest Lap Speed" using a Decision Tree Regressor and compare the performances for both. 


The data use was obtained from tidytuesday, https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-09-07/readme.md, and was cleaned using R to obtain a set of variables and a data set that was used for the analysis. The cleaning script "F1 Data - Cleaning Script.Rmd" and clean data set "Formula_One.csv" are attached to this repository. The file "Multiple Linear Regression - Alex Gichuki" contains a document with the R code and output used to build and select the best Multiple Linear Regression model to answer the question. The file "Decision Tree Regressor -Alex Gichuki.pdf" contains a document with the Python code and output used to build a Decision Tree Regressor.
