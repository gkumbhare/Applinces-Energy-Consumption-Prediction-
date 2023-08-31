# Applinces-Energy-Consumption-Prediction-

The Dataset is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network.Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes. The energy data was logged every 10 minutes with m-bus energy metres. Weather from the nearest airport weather station(Chievres Airport,Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes. You need to predict the energy use of appliances.


![image](https://github.com/gkumbhare/Applinces-Energy-Consumption-Prediction-/assets/122550001/83cc691d-fc4b-4e5b-9198-8e74268ffd55)


# Problem Statement
The Dataset is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network.Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes. The energy data was logged every 10 minutes with m-bus energy metres. Weather from the nearest airport weather station(Chievres Airport,Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes. You need to predict the energy use of appliances.

# Conclusion
In conclusion, the "Random Forest Regressor with GridSearchCV" model appears to be the best-performing model based on testing accuracy. However, given the high training accuracy, it's important to further investigate potential overfitting issues and consider strategies to mitigate them, such as hyperparameter tuning and feature selection. Additionally, the cross-validated XGBoost model also provides strong results and might be worth considering due to its good balance between bias and variance.
