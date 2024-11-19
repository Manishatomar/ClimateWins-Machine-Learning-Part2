# Navigating Climate Change with Machine Learning
Utilizing a combination of unsupervised learning techniques (dendrograms) and supervised machine learning algorithms (CNN, RNN, Random Forest), along with principal component analysis (PCA) and hyperparameter optimization, to design a robust forecasting strategy for ClimateWins.
# Context
ClimateWins, a nonprofit organization, is committed to addressing the challenges of climate change, with a focus on the rising frequency of extreme weather events across mainland Europe over the past 10 to 20 years. The organization sees advanced tools, such as machine learning, as crucial for predicting and mitigating these weather extremes. By utilizing weather data from the past century, ClimateWins aims to develop a predictive model to gain insights into future weather patterns and enhance preparedness.
Key Questions
* Identify weather patterns outside the regional norm in Europe.
* Determine if unusual weather patterns are increasing.
* Generate possibilities for future weather conditions over the next 25 to 50 years based on current trends.
* Determine the safest places for people to live in Europe over the next 25 to 50 years.
# Data Source
The [data set](https://github.com/Manishatomar/Dataset/blob/main/Dataset-weather-prediction-dataset-processed.csv) is based on weather observations from 18 different weather stations across Europe, which contain data ranging from 1960 to 2022. Recordings exist almost daily with values such as temperature, wind speed, snow, global radiation, and more. This data is collected by the [European Climate Assessment & Data Set project](https://www.ecad.eu/). An [additional data](https://github.com/Manishatomar/Dataset/blob/main/Dataset-Answers-Weather_Prediction_Pleasant_Weather.csv) set was employed to train the ML models. This data set categorizes each day as either 1 or 0, indicating whether the weather was considered pleasant or not. Moreover, a dataset consisting of images representing four weather categories—cloudy, rain, sunshine, and sunrise—was used to train a visual weather recognition model.
