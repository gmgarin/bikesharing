# bikesharing
Data Visualization using Tableau

## Overview of the Statistical Analysis:
### The main goal of this project was to visualized data extracted from [Citi Bike trip history data](https://s3.amazonaws.com/tripdata/index.html). The bike trip analysis were done using these data. Pandas was also used to convert "tripduration" parameter into datetime data type. A set visualizations was done to:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

## Results
### As as as result of the analysis, the following graphs were created:
![This is an image](https://github.com/gmgarin/bikesharing/blob/f30bbb124c6ab4f663d13e1917e7d17eeb05a357/Resources/Dashboard%201.png)

## [Link to dashboard](https://public.tableau.com/app/profile/genesis.garin.villemaire/viz/TableauChallenge_16502185651750/Story)



### Number of Trips

![This is image](https://github.com/gmgarin/bikesharing/blob/0cc9ff41b2dc6a4cbe2f9ca2899d4a971a939e60/Resources/Number%20of%20Trips.png)

- This is the amount of data that were recorded and analyzed for the month of August 2019.

### Checkout Times for Users
![This is image](https://github.com/gmgarin/bikesharing/blob/0cc9ff41b2dc6a4cbe2f9ca2899d4a971a939e60/Resources/Checkout%20Times%20for%20Users.png)

- The graph shows that most trips end in under an hour duration. 

### Checkout Times by Gender
![This is image](https://github.com/gmgarin/bikesharing/blob/0cc9ff41b2dc6a4cbe2f9ca2899d4a971a939e60/Resources/Checkout%20Times%20by%20Gender.png)

- The graphs shows the breakdown of trip duration by gender. Most bike riders who identified themselves as "male" are higher in number than the other categories. It can also be said that "female" and "unkwown" riders tend to take longer trips than "male" riders."

### Trips by Weekday per Hour
![This is image](https://github.com/gmgarin/bikesharing/blob/00b7749c4835ee92a74aa78bd9803f73b8702eab/Resources/Trips%20by%20Weekday%20per%20Hour.png)

- The heatmap above shows the peak hours when most bikes are being utilized. The hours between 6:00am and 9:00am, and 4:00 pm and 7:00 pm during Monday through Friday, seem to be the time when most users ride Citi Bikes. However, during the Saturday and Sunday, the peak hours are between 9:00 am and 7:00 pm.

### Trips by Gender (Weekday per Hour)
![This is image](https://github.com/gmgarin/bikesharing/blob/00b7749c4835ee92a74aa78bd9803f73b8702eab/Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour)%20.png)

- The heatmaps above shows the comparison between genders in terms of peak hours during the day. The hours between 6:00am and 9:00am, and 4:00 pm and 7:00 pm during Monday through Friday, seem to be the time when the number of male bike riders are greater than female and unknown users. This seems to be trend as well during the weekend.

### User Trips by Gender by Weekday 
![This is an image](https://github.com/gmgarin/bikesharing/blob/daf1ee18cddda265f1ef17077eff5a239a55de1f/Resources/User%20Trips%20by%20Gender%20by%20Weekday%20Viz.png)

-  The heatmap above shows that "male" identifies users are greater than the other two categories. Furthermore, there are more "male" subscribers use the Citi Bike from Monday through Friday.

### Top Starting and Top Ending Locations
![This is an image](https://github.com/gmgarin/bikesharing/blob/daf1ee18cddda265f1ef17077eff5a239a55de1f/Resources/Top%20Starting%20Location.png)

![This is an image](https://github.com/gmgarin/bikesharing/blob/f8823c0462cbfec7f7c12687a07270d87b9ff8a8/Resources/Top%20Ending%20Location.png)

- The heatmaps above show where riders in New York City start and end their trips. Looking at the two maps, it can be said that both are largely similar. Meaning that both maps are shows many starting points are also the ending points of the many Citi Bike users in New York City.

## Summary 
### In conclusion, bike ride services, like the Citi Bike, are very common and in demand in large cities like New York. With over 2 million trips recorded just for the month August in 2019, it can be a inferred that this is a good alternative and popular mode of transportation, especially to male subscribers.

### However, two additional analysis and visualization for future reference are:
- comparison of data (such as number of subsribers and trips) among competitors.
- number of accidents recorded involving Citi bikes.