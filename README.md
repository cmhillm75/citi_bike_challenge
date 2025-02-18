# citi_bike_challenge

Tableau module 18. I chose to use a summer vs winter comparison of citi_bike data. My `Resources` folder
contains the original downloads `JC-202406-citibike-tripdata.csv` and `JC-20412-ciitbike-tripdata.csv`.
I used jupyter notebook, created 2 DataFrames and added 2 columns of information, "trip_distance_miles" and
"trip_duration_min". I then saved the updated csv files as `june_bike.csv` and `december_bike.csv`.

## Links

[Citi Bike page](https://citibikenyc.com/system-data)

## June Findings

Members vs. Casual Riders (June Data):

- Total Rides (111,061):

Members: 78,646 rides = 70.81%

Casual: 32,415 rides = 29.19%

- Total Riding Time:

Members: 678,636 minutes = 50.27%

Casual: 671,237 minutes = 49.73%

- Average Ride Time:

Members: 8.63 minutes

Casual: 20.71 minutes

- Total Miles:

Members: 58,000 miles = 68.15% of all miles biked.

Casual: 27,105 miles = 31.85% of all miles biked.

- Type of bike used:

electric_bike: 64,190 or 57.8% of all rides.

classic_bike: 46,871 or 42.2% of all rides.

## December Findings

Members vs. Casual Riders (December Data):

- Total Rides (54,817):

Members: 45,178 = 82.42%
Casual: 9,639 = 17.58%

- Total Riding Time:

Members: 327,196 minutes = 77.04%

Casual: 97,519 minutes = 22.96%

- Average Ride Time:

Members: 7.242 minutes

Casual: 10.117 minutes

- Total Miles:

Members: 32,342 miles = 80.45% of all miles biked.

Casual: 7,860 miles = 19.55% of all miles biked.

- Type of bike used:

electric_bike: 37,265 or 67.98% of all rides.

classic_bike: 17,552 or 32.02% of all rides.

## Key Observations

Ride Frequency: Members take significantly more rides than casual riders. The member share of rides was 9.64% greater in December than June.
The signifcant decrease in Casual rides in December is easily explainable in temperature usage. Members are more likley using as transportation
vs leisure.

Total Time: In December Members accounted for > 3x the amount of minutes biked where there was only a slight lead in total minutes 50.27%
to 49.73%.

Average Ride Duration: June Casual rides are 140% longer than Member rides on average however that decreased to just 39.73% in December.

Distance Covered: In June there was 85,105 miles ridden, Members accounted for 68.15% of those. In December 40,202 miles were biked
and their share increased to 80.45% despite fewer total riding minutes.

Electric vs Pedal: Riders favored using electric_bike more than 2 to 1 in December where due to higher volume in June only had a 15%
greater usage. When comparing December to June and Members accountinig for the majority of rides, the transportation usage by Members
is supported.

Possible Insights:
Commuters vs. Leisure Riders: Members might primarily use bikes for shorter, frequent trips (e.g., commuting), while casual riders
might be using bikes for longer average ride times, possibly recreational trips as the June data show that the durations were more than 2x longer
than member riders. The casual segment appears to not participate when the temperatures drop. There does appear to be a strong engagement for Members
which suggests a loyal user base. Our map comparison shows that the majority of bike activity takes place in the Jersey City and Hoboken areas.