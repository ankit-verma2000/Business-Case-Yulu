# Business-Case-Yulu
![image](https://github.com/user-attachments/assets/0a5334f0-a09c-481a-9fe2-72f30c1c7919)


# About Yulu

* Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

* Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

* Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

# How you can help here?

* The company wants to know:
  
1. Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
2. How well those variables describe the electric cycle demands

# Dataset:
Dataset Link: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089

# Column Profiling:

* datetime: datetime
* season: season (1: spring, 2: summer, 3: fall, 4: winter)
* holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
* workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
* weather:
  1. Clear, Few clouds, partly cloudy, partly cloudy
  2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
* temp: temperature in Celsius
* atemp: feeling temperature in Celsius
* humidity: humidity
* windspeed: wind speed
* casual: count of casual users
* registered: count of registered users
* count: count of total rental bikes including both casual and registered

# Concept Used:

* Bi-Variate Analysis
* 2-sample t-test: testing for difference across populations
* ANNOVA
* Chi-square


---------------------
# Data Insights: 

- Analyzed 10,886 Yulu bike rental data points from January 2011 to December 2012.

𝐊𝐞𝐲 𝐌𝐞𝐭𝐫𝐢𝐜𝐬:Assessed bike rentals based on weather, seasonality, and time of day.

𝐒𝐞𝐚𝐬𝐨𝐧𝐚𝐥 𝐓𝐫𝐞𝐧𝐝𝐬: Identified higher demand during summer and fall, with winter having the highest rentals.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐁𝐞𝐡𝐚𝐯𝐢𝐨𝐫:Peak rentals occurred between 12 PM and 6 PM, with similar demand on weekdays and weekends.

𝐖𝐞𝐚𝐭𝐡𝐞𝐫 𝐈𝐧𝐟𝐥𝐮𝐞𝐧𝐜𝐞: Clear weather had 7,192 rentals, while heavy rain led to only 1 rental.

𝐓𝐞𝐦𝐩𝐞𝐫𝐚𝐭𝐮𝐫𝐞 & 𝐇𝐮𝐦𝐢𝐝𝐢𝐭𝐲: Rentals peaked between 20.5°C and 26.24°C, with higher humidity reducing demand.

𝐒𝐭𝐚𝐭𝐢𝐬𝐭𝐢𝐜𝐚𝐥 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬: No significant difference in rentals between working and non-working days.

𝐀𝐜𝐭𝐢𝐨𝐧𝐚𝐛𝐥𝐞 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬: Recommended optimizing bike availability during peak periods, weather-based pricing, and seasonal marketing campaigns.

𝐓𝐞𝐜𝐡 𝐒𝐭𝐚𝐜𝐤: pandas · A/B Testing · SciPy · Python (Programming Language) · NumPy · Pandas (Software)
