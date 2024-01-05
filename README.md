# London bikes dataset analysis using Python

This project is about analyzing the number of bike riders in London and the relationships that exist with the weather factors.

## Description

The main focus of this project is to apply the data analysis process of identifying data, cleaning, analyzing, visualizing, and sharing it.

## The code

All the Python work existed in the main.ipynb file

## Key insights of this analysis are

#### Number of bike riders per month

![Number of bike riders per month](https://github.com/MoSbeaa/London_Bikes_Data_Analysis_Python/tree/main/img/1.png)

#####  Analysis:

1. Ridership peaks in the summer months (June, July, August), likely due to warmer weather and longer daylight hours.
2. Ridership dips in the winter months (December, January, February), likely due to colder temperatures and shorter days.
3. There's some variability in ridership even within the same season, suggesting other factors may also influence ridership, such as weather conditions, events, or promotions.

#####  Conclusions:

+ Seasonal patterns play a significant role in ridership, with higher numbers in summer and lower numbers in winter.
+ Other factors, such as weather conditions and events, may also influence ridership within seasons.

#### Correlation between all features
![Correlation between all features](https://github.com/MoSbeaa/London_Bikes_Data_Analysis_Python/img/2.png)

#####  Analysis:

1. Positive correlations:
    * Temperature: The strongest positive correlation is with temperature (0.39) to the count of riders. This means that as the temperature increases, the number of bike rides also increases. This is likely because people are more comfortable and enjoyable to bike in warmer weather.
    * Feels like temperature: There is also a positive correlation with "feels like" temperature (0.37), which suggests that perceived temperature may be just as important as actual temperature in influencing ridership.
    * Wind speed: There is a weak positive correlation with wind speed (0.12). This could be because a slight tailwind can make cycling easier, but strong winds may deter people from biking.
    
2. Negative correlations:
    * Humidity: There is a moderate negative correlation with humidity (-0.46). This means that as humidity increases, the number of bike rides decreases. This could be because people find cycling less comfortable in humid weather.
    
    
#####  Conclusions:

+ Warm and dry weather encourages biking: Higher temperatures and lower humidity correlate with a higher number of bike rides. This suggests people prefer comfortable conditions for cycling.
+ Rain and humidity discourage biking: Strong negative correlations with precipitation and rain with thunderstorms indicate a clear deterrent effect on ridership.
+ Other factors like wind speed have smaller impacts: A weak positive correlation with wind speed suggests a slight influence, but not as significant as temperature and humidity.

+ This analysis shows associations, not causal relationships. Factors like seasonality and urban infrastructure may also play a role.

#### Number of bike riders by weather
![Number of bike riders by weather](https://github.com/MoSbeaa/London_Bikes_Data_Analysis_Python/img/3.png)

#####  Analysis:

1. Clear skies and broken clouds are most popular for biking: The highest number of bike riders, 1496, is observed during roken clouds skies, followed closely by 1195 riders during broken clouds side to side with clear skies of 1162. This suggests that people generally prefer to bike when there's ample sunshine or partial cloud cover.

2. Rain, snowfall and thunderstorms significantly reduce ridership: Rain with thunderstorm and snowfall have the most dramatic impact on ridership, with only 583 and 251 riders, respectively. This is likely due to safety concerns, discomfort, and reduced visibility during these conditions.

#####  Conclusions:

+ Weather conditions play a significant role in bike ridership.
+ Clear skies and scattered clouds are the most favorable for biking.
+ Rain, thunderstorms, and snowfall have a negative impact on ridership.


#### Relationship between temperature and number of bike riders
![Relationship between temperature and number of bike riders](https://github.com/MoSbeaa/London_Bikes_Data_Analysis_Python/img/4.png)

#####  Analysis:

1. The data points form a roughly upward-sloping trendline, indicating a positive correlation.
2. There is a noticeable increase in the number of bike riders above 15 degrees Fahrenheit.
3. The number of bike riders appears to plateau or even decrease slightly at the highest temperatures.

#####  Conclusions:

+ Comfort: People are more likely to bike when the weather is comfortable. When it is too cold or hot, they may choose to stay indoors or use another mode of transportation.
+ Safety: Biking can be dangerous in extreme weather conditions, such as ice or snow. People may be less likely to bike when the weather is unsafe.
+ Enjoyment: Biking can be a more enjoyable activity when the weather is pleasant. People may be more likely to bike when they know they will have a good time.

#### Number of bike riders by weekend or not
![Number of bike riders by weekend or not](https://github.com/MoSbeaa/London_Bikes_Data_Analysis_Python/img/5.png)

##### Analysis:

1. Number of riders in weekdays is triple number of riders in the weekend days

##### Conclusions:

+ The significant majority of bike riders (75.6%) prefer riding on weekdays compared to weekends (24.4%). The reasons for this distribution could vary and might be influenced by factors such as commuting patterns, work schedules, or other external factors.
