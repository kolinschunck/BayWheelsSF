# The Customer Behaviour Trend Insights Report of Bay Wheel's Bike Service in the SF Bay Area

<span style="color: gray; font-size:1em;">Kolin Schunck</span>
<br><span style="color: gray; font-size:1em;">April 27, 2020</span>


## Introduction

Bay Wheels is a regional public bicycle sharing system in the San Francisco Bay Area, California operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. On June 28, 2017, the system officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was subsequently renamed to Bay Wheels in June 2019. The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

The bicycles are available 24 hours a day, seven days a week for periods ranging from a single ride (up to 30 minutes) to a day pass, in 30-minute increments, or customers can purchase an annual subscription which gives them unlimited rides up to 45-minutes in duration. Single rides cost USD2 per trip, day passes cost USD10 per day, and memberships cost USD15 per month or USD149 per year.

A reduced pricing option called "Bike Share for All" exists for users who qualify for CalFresh, the SFMTA's Lifeline pass, or PG & E's CARE discount. The reduced price is USD5/year for the first year and USD5/month in subsequent years. This membership option provides rides of 60 minutes without an additional charge. As of January 2018, around 15% of the membership of the bikeshare system used the Bike Share for All option.


## Dataset

This document explores the Bay Wheel's trip data of bike rides for the FY2019. The variables include the trip start/end time, as well as additional features such as user type, and trip duration. The dataset was extracted from the lyft website. The data can be found [here](https://s3.amazonaws.com/baywheels-data/index.html), with feature documentation available [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Summary of Findings

- People use this service on weekdays more than weekends.
- 8am and 5pm are the peak hours for this service. Also, people use this service when they are in lunch time as well.
- Percentage of subscribers is 80.62%. Percentage of customers is 19.38%.
- Customers' rides seems increasing slightly but subscibers' rides reached more than customers' in general. There is a decrease in November 2019 for subscribers but it seems like it is related with winter season.
- Subscribers' average trip duration is around 12 minutes. Customers' average trip duration is around 23 minutes.
- Subscribers and customers trip distance were 1.25 and 1.75 respectively.
- The majority of bike rides take place on weekday.
- The peak bike rides time for all members is around commute time.


## Key Insights

Renting a bike from Bay Wheel's bike service is a great way to move around the city or SF Bay area, either for pleasure or work. Two types of customer groups are identfied: (1) Subscribers and (2) Casual Riders. Subscribers use the service mainly for commuting to/from work, whereas Casual Riders are most likely tourists or occassional riders to use the service for exploring the Bay area. Further, subscribers represent the largest group (81%) who rent a bike during the weekdays mostly between 7am-9am as well as 4pm-6pm. There are also minor usages during lunch hours. The subscriber group should be handled with care by Bay Wheel's as they are the largest group, having a great impact on the overall business for the company.

### Trend Insight 1: Subscribers are the heavy-user group of the bike ride system
Customers with a monthly membership ("Subscriber") make 81% of all customers in FY 2019 that used the system. 19% were casual riders ("Customer") using the bike share system ocasionally, upon demand. Casual riders ("Customer") continously increase in terms of absolute figures in FY 2019. Monthly membership users stayed on avg. relatively stable, with a sharp decline beginning in November. This is most likely b/c of the beginning of the winter season. Monthly subscribers then probably pause or cancel their membership and re-activate it once the winter season is over.

### Trend Insight 2: Usage varies by user groups significantly
Customers with a monthly subscription use the bike ride system for approx. 12 min. per bike ride on average. The surprising fact is that casual riders almost use the system twice as long, namely 23 min. The average distance also varies slightly, as casual riders ride on average 1.75 miles, whereas subscription members ride 1.25 on average. This confirms the overall findings that subscribers use the system to go to/from work, wherea casual riders could be tourists or others spending time in the SF Bay Area to explore certain areas of the city.

### Trend Insight 3: Subscribers are more active during weekdays, whereas the opposite is true for casual riders
- Casual Riders use the bike sharing system more often on weekends:
(1) weekdays: most bike rides hapen around 8-9am and 5-6pm with the peak on Fridays around 5pm
(2) weekends: most bike rides happen between 10am - 8pm with the peak on Saturdays around 2pm
- Subscribers use the bike sharing system mainly on weekdays:
(1) weekdays: most bike rides hapen around 8-9am and 5-6pm with the peak on Tuesdays around 8am
(2) weekends: bikes are still rented but there is a significant drop in numbers of rented bikes throughout the entire weekends

## Feedback

Feedback has been collected from two professionals working in the travel and mobility tech ecosystem. The feedback included mainly the visualizations of the different diagrams in the presentation deck. Further, it was suggested to add another data perspective to the slide deck, namely the average distance of each of the user groups.

## Resources

- Udacity video lecture material
- Python and pandas documentation
- Stackoverflow, for exmaple for: extraction of month, day, year from data frame
- Wikipedia
