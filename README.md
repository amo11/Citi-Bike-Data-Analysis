# citi-bike-data-analysis

## Project Overview
This project aims to comprehensively analyze the one year’s (2023) data of Citi Bike sharing system in NYC. The report contains graphs showing peak hours, total rides during weekday/weekend/holiday, pattern of rides during various weather condition and popular routes for each type of riders. 

## Introduction
In a bustling city of New York, where millions of tourists, commuters, urban habitants commute every day, a sustainable, flexible and affordable transport ecosystem becomes lifeline of the city.
<br/>
Hence, to avoid the hefty cab price and traffic, the city provides a number of transportation options such as metro, bus, ferry, subway, rail, Citi Bike etc. One of the easy, quick, affordable and fun commute options is Citi Bike which has gained a lot of attraction in last few years.  Established in 2013, Citi Bike sharing system has seen a substantial growth in the bike riders. Hence, to understand how the Citi bikes move within the city, this report focuses on how various factors such as weekday/holiday, weather, rider’s types makes the pattern of rides. 

## Data collection
The study uses publicly available data from [Citi Bike web portal](https://citibikenyc.com/system-data) for the year 2023. Their data for the months of March, July, October and December has been analyzed.

The Citi Bike dataset contains below variables:

| <ins> Variables </ins> | <ins> Description </ins> |
| :-------: | :----------: |
|  Rideable type  | A unique ID for each ride |
| Started at | Time stamp of each ride when started |
| Ended at | Time stamp of each ride when ended |
| Start station name | Address of start station |
| Start station ID | Unique ID of the station where a trip started |
| End station name | Address of end station |
| End station ID | Unique ID of the station where a trip ended |
| Start latitude/ Start longitude | Geographic coordinates of start station name |
| End latitude/ End Longitude | Geographic coordinates of end station name |
| Member or casual ride | Member- Rider having membership Casual – Rider having one day (24 hours) subscription|

## Analysis
 + *Rush Hours (July)*
   
   The below graphical representations indicate different rush hours for each user type i.e. Members and Casuals.

   ![Rush Hour-member](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/823d3f4f-41ca-4482-bf93-970637d3941c)

   We see two peaks for Members, one at 8 AM and another between 4 PM to 7 PM. Thus, we can predict that majority of the Members are 
   doing job or working professionals or students.
   
   ![Rush Hours(Casuals)](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/98cff7c4-ebb3-4244-a282-8213975259a3)

   There is a curve observed for Casuals with maximum number of riders between 5 PM to 6 M with majority of Casuals being tourists/travelers who would love to explore the top attractions of the city and witness beautiful sunset from magnificent skyline of NYC. 

 + *Daily Ride Analysis*
   
   By analyzing July data, we see a fine correlation between number of riders and a particular day(weekday/weekend/holiday).

   ![Daily ride analysis- members](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/77a736dd-723f-4872-b89d-ec538abf44f4)

   The number of member riders are quite high on weekday compared to weekends pertaining to the fact that the majority uses the Citi Bikes as the mode of commute to work. A special case of 4th July, when the number of Member riders are less even if it is a weekday. This is because it’s a National holiday celebrated as Independence Day.

   ![Daily ride analysis- casuals](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/ada76017-6a70-4227-8bf1-287ca13d2594)
   Conversely, the number of Casuals is more on weekends than on weekdays due to the fact that they usually do fun rides during the free time.

   Quite similar trend with approximately same number of riders as July is observed in the month of October.

   A similar trend has been observed for the month of March and December but with significant reduction in number of total rides (58%). Below showcases the trend for the month of March.

   ![Daily ride analysis-members(March)](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/73aeed45-6985-418f-b941-21d9a41eff25)

   ![Daily Ride Analysis - March (casuals)](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/dc4aaecf-ceca-4149-b9dd-ea980244789c)

   The variation in total number of riders in different months can be attributed to the season during a particular month i.e. winter, spring, summer, autumn.

 + *Seasonal*
   
   To understand the seasonal trend of the Citi Bike riders, I have grouped twelve months of a year in four seasons. i.e. Winter (December, January, February), Spring (March, April, May), Summer (June, July, August), Autumn (September, October, November).

   ![Seasonal](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/45ff638a-70d2-4a97-94b1-57e2852d97e9)

The greatest number of riders is observed in Summer clearly due to favorable weather conditions for bike riders which gradually decreases leaving us with the least number of riders in Winter due to odd weather conditions. This is quite self-explanatory. 

+ *Electric Bike Trend*
  
  With increasing popularity of electric vehicles, it’s quite interesting to see how the electric bikes of Citi Bike is doing in NYC.

  ![Electric Vehicle trend](https://github.com/amo11/citi-bike-data-analysis/assets/169110417/32a8f3cc-5e34-47a6-a127-628c940ab8d4)

  The above represents the downward trend for the electric bikes. Started with approx. 19.6% share of total rides in January goes down to 3.44% share of total rides in December. This is quite intriguing and it prompts us to identify the reason/s - if there is a lack of infrastructure for the electric bike in NYC? Or are there any operational issues (such as less speed, heavy body, bad look and feel) faced by riders? Or the pricing for electric bike is not affordable to riders? Or are there any other hidden issues/reasons for losing traction of electric bikes? A detailed survey/feedback from riders can be helpful to address the issue.



 

