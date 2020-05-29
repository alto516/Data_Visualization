# (Bikes Data Exploration)
## by Jeong ha, Park


## Dataset
> There are 404,947 bikes in New York with features. 
(New York : Trip_Duration, Start_Time, End_Time, Start_Station, End_Station, Bke_ID, User_Type,  Birth_Year, Gender, Start_Hour, End_Hour, Start_Noon, End_Noon, Start_Month, Start_Weekday)

> Type of Trip_Duration variable is originally int and its statistic is expressed with other types. So I made original Trip_Duration divide Trip_Duration(s): seconds, Trip_Duration(m):minutes. I also made new columns, Start_Hour, End_Hour, Start_Noon(AM/PM), End_Noon, Start_Month, Start_Weekday for good analysis. It has total 16 data columns .
And the variables User_Type, Gender, Trip_Route and Passholder are categorical types with the following.

Gender : Female, Male, Unknown <br>
User_Type : Subscriber, Customer <br>
Trip_Rout : One Way, Round Trip <br>
Passholder : Walk-up, One Day Pass ,Monthly Pass, Annual Pass, Flex Pass ,Testing <br>
Bike_Type : Standard, Electric, Smart <br>
Start_Hour : 0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23 <br>
Start_Noon : AM, PM <br>
Start_Month : 1,2,3,4,5,6,7,8,9,10,11,12 <br>
Start_Weekday : Sunday,Monday,Tuesday, Wednesday, Thursday,Friday,Saturday <br>


## Summary of Findings

> First, the number of subscribers is about seven times more than the number of general customers.
> NExt, the number of times the bicycle was used for each day of the month. The monthly analysis of the days of the most used bicycles is as follows:
January: Wednesday, February: Thursday, March: Friday, April: Tuesday, May: Wednesday / Friday, June: Saturday, July: Tuesday / Wednesday, August: Friday / Saturday, September: Monday / Wednesday, October: Tuesday, November: Friday, December: Tuesday

> The analysis shows that there is no particular relationship between specific days of week and frequency of use. The most significant result in the frequency by month of year, as mentioned earlier, is the highest rate of bicycle use between May and October.

>In addition, the number of times the bicycles were used for each day of each month was analyzed by user type. The results showed the same trend monthly, so there was no big difference by user type.

> As a result of comparing and analyzing daily / monthly bicycle use rate and each hour / day use rate, the rate of daily / monthly bicycle use rate showed similar trend and the difference was not known. However, it was found that the difference in frequency of use by hour and week differs significantly between weekend and weekday.

## Key Insights for Presentation

> The vast majority (98.44%) ride their bikes for less than an hour. Cycling time for subscribers, general customers, and bicycles was estimated to be about 4 to 10 minutes. People riding more than one hour account for 1.56%, but they act as ourlier to the overall data trend.
> People use it more in the afternoon than in the morning, and the frequency of cycling between 7 am-8pm and 5 am-7pm is related to commute time. According to the monthly usage rate is high evenly from April to November. Other months seem to be related to temperature due to low utilization rates. In the warmer season, the rate of bicycle use is high. According to the user-specific analysis for each day of the week, subscribers are usually high on weekdays, while regular customers are high on weekends. Subscribers are more likely to sign up for bikes to commute during the week. On the other hand, it is estimated that ordinary customers used bicycles for leisure time on weekends.