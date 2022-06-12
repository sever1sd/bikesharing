# NYC Citi Bike Analysis

## Purpose
The purpose of this analysis was to review publicly available data on the company Citi Bike in order to determine the viability of a similar company in another location.

The data was primarily focused on the customer usage statistics and demographic landscape. The customer and usage data was sourced from New York City and the surrounding areas.

The goal is to determine if the same business model could be used in Des Moines, Iowa. 

## Analysis

Pandas and Jupyter Notebook were used to clean the data and Tableau was used to create data visualizations. 

Access to the Tableau dashboards can be found at the following links:


[Tableau Story Analysis](https://public.tableau.com/app/profile/shane.sever/viz/NYCCitiBikeAnalysis_16550456824600/Story1?publish=yes)


## Results

In order to understand the viability of this business model it is important to determine when, where, and how the current customers are using the service.

**Starting Location**
![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Top%20Starting%20Locations.png)

This graph maps the starting points for each ride. The primary use of the service is within the NYC metropolis area. This could be due to tourism, but more likely it is a result of denser population.

**Ending Location**
![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Top%20Stopping%20Locations.png)

This graph maps the ending points for each ride. This is corroborated by the ending location. Most rides end roughly in the same area as where they started. Indicating the service usage may be localized to highly dense populations or areas of high tourism.

**Trips by Weekday**
![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Trips%20by%20Weekday%20Per%20Hour.png)

This graph determines what days of the week the service is being used. Generally, the service is utilized on weekdays during peak commute areas. This indicates that the service is likely not used for tourism and is instead used as an alternate commute method other than public transportation or vehicles.

There is some usage during the weekends, which could be attributed to tourism. But the service is predominantly used during the week.

**Trips by Gender**

![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

This graph is the same as the previous, but including gender as a datapoint. When the data is cut by gender, we see the same weekly usage patterns. However, the service is largely utilized by males during peak commut hours.

**User Type**

![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Uster%20Trips%20by%20Gender%20by%20Weekday.png)

This graph also evaluates weekly usage by gender, but includes the customer type. Interestingly, when evaluating the same data through "user type" -- which is defined as either a "customer" or "subscriber" -- we find that the predominant users are subscribers to the service. Subscribers also tend to be mail and the weekdays remain a popular time to use the service.

**Trip Duration**

![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Checkout%20Time%20for%20Users.png)

This graph illustrates the duration of trips. Most trips are 20 minutes or less. The duration of trips peaks at around 10 minutes and then tapers steeply off until about 40 minutes. No trips go longer than hour.

**Trip Duration by Gender**

![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Checkout%20Time%20by%20Gender.png)

This graph is similar to the previous graph, but includes gender as a datapoint. Gender does not seem to impact the duration of the trips. Rather, this graph seems to continue to corroborate that the majority of users are males. 

## Summary

Ultimately, the data appears to reveal that the usage of this service is located predominatly in densely populated areas, used by males, and is a primary means to commuting to and from work. Additionally, most users of the service are long-term subscribers whereas there seems ad hoc usage appears to be sparse.

When considering transferring a similar business model to Des Moines, Iowa, it will be important to consider local demographics carefully. Additional visualizations on local data would be helpful (this would require additional data), for example:

1. Demographic break downs of Des Moines, Iowa.
2. Population data for the city of Des Moines, Iowa.

Additionally, some information on the cost effectiveness of the existing model in NYC would be useful. One such example would be the cost and frequency of repairs. An estimated frequency of repair can be seen in the below graph:

![alt](https://github.com/sever1sd/bikesharing/blob/b2ee605f4ca4e5c32ffc54d5731b735fbeacffd0/Images/Bike%20Repairs.png)

This graph evaluates the total number of times a bike is used and attempts to estimate its need for repair. Bikes that are used more are on the outer circle and will likely need repairs more frequently. This could be costly, particularly for a new business in a new location.