# Seoul Bike Sharing Demand Prediction(linear regression)
Seoul Bike Sharing Demand Prediction(linear regression)
# Abstract:
Bike sharing as we know is a transport service primary focus to lend conventional or electrical bikes to an individual or a group of individuals in order to let them travel in city or outskirt in rent for an hour, a day or for a month depending on the needs.

In market share we can see that Bike Sharing system has a global market share which was valued around 3.39 billion Dollars in 2019 and is projected to grow to 6.98 Billion Dollars by 2027 with a compound annual growth rate of around 14% indicatively from 2020 to 2027.

Several factors such as low bike rent, increase in capital investments,introduction of e-bikes in the market, technological advancement and government schemes for development of several bike-sharing infrastructure has increased the overall market share and led to the introduction of several opportunities during the forecasted year. However, rise in bike theft and huge initial investment are some of the key factors in order to hinder expected market growth.

Keywords: Bike-Sharing, Data Mining, Predictive Analysis, Linear Regression, Machine Learning.

# Introduction:
Bike sharing system demand nowadays is increasing in proportional manners globally. This system has gained a lot of attention with its cost effective system and easy to use nature. This system has already attracted a huge customer base globally like in South Korea, São Paulo ,China and Australia. Bike sharing system generally rents bikes on an hour, day and month basis and is generally based on static pricing inclusive of hour,days or month. Because of its affordability and easy renting system anyone can commute on arrival. According to our problem our main aim is to build a predictive model so as to find the number of bikes rented based on the given dataset.
# Problem Description:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
# Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
* Attribute Information:
* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Feature Description:
* Date : Date feature which is str type is needed to convert it into Datetime format DD/MM/YYYY.The new feature extracted from Date are Day, Month and year
* Rented Bike Count : Number of bike rented which is our Dependent variable according to our problem statement which is int type.
* Hour: Hour feature which is in 24 hour format which tells us number bike rented per hour is int type.
* Temperature(°C): Temperature feature which is in celsius scale(°C) is Float type.
* Humidity(%): Feature humidity in air (%) which is int type.
* Wind speed (m/s) : Wind Speed feature which is in (m/s) is float type.
* Visibility (10m): Visibility feature which is in 10m, is int type.
* Dew point temperature(°C): Dew point Temperature in (°C) which tells us temperature at the start of the day is Float type.
* Solar Radiation (MJ/m2): Solar radiation or UV radiation is Float type.
* Rainfall(mm): Rainfall feature in mm which indicates 1 mm of rainfall which is equal to 1 litre of water per metre square is Float type.
* Snowfall (cm): Snowfall in cm is Float type. Seasons: Season, in this feature four seasons are present in data is str type.
* Holiday: whether no holiday or holiday can be retrieved from this feature is str type.
* Functioning Day: Whether the day is Functioning Day or not can be retrieved from this feature is str type.
* Weekend : Weekend extracted from Day 1 when the day is Saturday or Sunday while 0 when weekdays
