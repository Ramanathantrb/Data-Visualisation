# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This dataset is mainly focused on the various types of delays and the duration of these delay. it is an extensive database of over 20 years. Data is categorised based on the carrier,airport and carrier code.

year: The year of the data record, indicating when the flight occurred.
month: The month of the data record, indicating when the flight occurred.
carrier: The airline carrier code, representing the airline responsible for the flight.
carrier_name: The name of the airline carrier.
airport: The airport code, representing the departure or arrival airport.
airport_name: The name of the airport.
arr_flights: The total number of flights that arrived at the airport.
arr_del15: The number of flights that arrived 15 minutes or more late.
carrier_ct: The number of flights delayed due to carrier-related issues.
weather_ct: The number of flights delayed due to weather-related issues.
nas_ct: The number of flights delayed due to National Aviation System (NAS) issues.
security_ct: The number of flights delayed due to security-related issues.
late_aircraft_ct: The number of flights delayed due to late aircraft arrival.
arr_cancelled: The number of flights that were canceled.
arr_diverted: The number of flights that were diverted to an alternative airport.
arr_delay: The total number of minutes of arrival delay for all flights.
carrier_delay: The total number of minutes of arrival delay attributed to carrier issues.
weather_delay: The total number of minutes of arrival delay attributed to weather-related issues.
nas_delay: The total number of minutes of arrival delay attributed to NAS issues.
security_delay: The total number of minutes of arrival delay attributed to security-related issues.
late_aircraft_delay: The total number of minutes of arrival delay attributed to late aircraft arrival.  

>Dataset looks clean and tidy.
only few values are missing. since we have lots of data we can safely drop those rows

## Summary of Findings

>Flight delays are right-skewed, with most flights experiencing short delays(mostly less than 50 minutes). Some outliers have exceptionally long delays.

>Different carriers have varying total arrived flights, indicating differences in market share and scale.
South west airlines has the most arrived flights

>2020 has the most cancelled history. it may be due to the pandemic

>Late aircraft has accounted for the most delay minutes followed by NAS issues

>Late aircraft, NAS delays, and carrier-related issues are the most common causes of flight delays.

>period between 2007 and 2017 has seen a drop in total number of flights, reason for it has to be investigated further

>November month has the least amount of cancellations while january has the most flights cancelled

>Flights exhibit variations over the years, potentially influenced by seasonal factors.note:data is not complete for 2023

>There is not a much deviation in flight arrival over the different months.suggesting flight arrivals are not cyclical

>There is a strong positive corelation between the Number of Flight Arrivals and Number of Delayed Flights

>similarly there is also positive corelation between Carrier Delay and Weather Delay

>Comair Inc is the most affected by weather. Aloha Inc and Hawaiian Inc. are most affected by carrier-related issues

>Correlations between delay types, such as weather and carrier delays, highlight interdependencies..
strong positive corelation of 0.84 between carrier delay and delay due to late aircraft

> It can be noted that least average flight delay happened on the year of 2020 and generally during the months of june and july the average flight delay time is maximum

>It was surprising to find april month has the most flights cancelled despite having below average flight arrival

>There is also a strong positive corelation (0.76) between NAS delay and delay due to alte aircraft

## Key Insights for Presentation

>It can be noted that least average flight delay happened on the year of 2020 and generally during the months of june and july the average flight delay time is maximum

>Comair Inc is the most affected by weather. Aloha Inc and Hawaiian Inc. are most affected by carrier-related issues

>November month has the least amount of cancellations while january has the most flights cancelled

>Different carriers have varying total arrived flights, indicating differences in market share and scale.
South west airlines has the most arrived flights