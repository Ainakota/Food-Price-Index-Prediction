# Food-Price-Index-Prediction

# Problem Statement

Create a model that can predict future values of the index with accuracy using a variety of variables that affect food prices, and assess the precision and dependability of the model's predictions.

The Food Price Index (FPI) is a measure of the monthly change in the international prices of a basket of food commodities. The FPI is calculated by the Food and Agriculture Organization (FAO) of the United Nations, and it tracks changes in the prices of cereals, dairy products, meat, sugar, and vegetable oils.

This project is to predict the Food Price Index (FPI) using machine learning algorithms with PyCaret, focusing solely on linear regression. We began by gathering historical data on the FPI from [FAO](https://www.fao.org/worldfoodsituation/foodpricesindex/en/) and the facors present are Meat, Cereals, Dairy, Oils, Sugar.

After evaluating the models' performance, The model with hihest accuracy was selected and used it to generate monthly forecasts of the FPI for the given values of Meat, Cereals, Dairy, Oils and Sugar. The results were promising, with our model achieving an accuracy of over 90% in predicting the FPI.

The data can also be found in the website of FAO [(click here)](https://www.fao.org/worldfoodsituation/foodpricesindex/en/)
