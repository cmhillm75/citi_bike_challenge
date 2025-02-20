# citi_bike_challenge

Tableau Module 18. I chose to use a summer vs winter comparison of citi_bike data. My `Resources` folder contains the original downloads `JC-202406-citibike-tripdata.csv` and `JC-20412-citibike-tripdata.csv`. I used Jupyter Notebook, created 2 DataFrames, and added 2 columns of information: "trip_distance_miles" and "trip_duration_min". I then saved the updated CSV files as `june_bike.csv` and `december_bike.csv`. Additional formulas were created in Tableau and required making copies of both `june_bike(copy).csv` and `december_bike(copy).csv`

## Links

[README and Data](https://github.com/cmhillm75/citi_bike_challenge.git)

[Tableau Vizz](https://public.tableau.com/views/citi_bike_story_17398497522060/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

[Citi Bike page](https://citibikenyc.com/system-data)

[citi_bike_story](https://public.tableau.com/views/citi_bike_story_17398497522060/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Data License Agreement
[Citi Bike Data Sharing Policy](https://ride.citibikenyc.com/data-sharing-policy)

## June Findings

### Members vs. Casual Riders (June Data)

- **Total Rides (111,061)**:
  - Members: 78,646 rides = 70.81%
  - Casual: 32,415 rides = 29.19%

- **Total Riding Time**:
  - Members: 678,636 minutes = 50.27%
  - Casual: 671,237 minutes = 49.73%

- **Average Ride Time**:
  - Members: 8.63 minutes
  - Casual: 20.71 minutes

- **Total Miles**:
  - Members: 58,000 miles = 68.15% of all miles biked
  - Casual: 27,105 miles = 31.85% of all miles biked

- **Type of Bike Used**:
  - electric_bike: 64,190 rides = 57.8% of all rides
  - classic_bike: 46,871 rides = 42.2% of all rides

## December Findings

### Members vs. Casual Riders (December Data)

- **Total Rides (54,817)**:
  - Members: 45,178 rides = 82.42%
  - Casual: 9,639 rides = 17.58%

- **Total Riding Time**:
  - Members: 327,196 minutes = 77.04%
  - Casual: 97,519 minutes = 22.96%

- **Average Ride Time**:
  - Members: 7.242 minutes
  - Casual: 10.117 minutes

- **Total Miles**:
  - Members: 32,342 miles = 80.45% of all miles biked
  - Casual: 7,860 miles = 19.55% of all miles biked

- **Type of Bike Used**:
  - electric_bike: 37,265 rides = 67.98% of all rides
  - classic_bike: 17,552 rides = 32.02% of all rides

## Key Observations

### Ride Frequency

Members take significantly more rides than casual riders. The member share of rides was 9.64% greater in December than in June. The significant decrease in casual rides in December is easily explainable by temperature changes. Members are more likely using bikes for short distance transportation versus leisure.

### Total Time

In December, members accounted for more than 3 times the amount of minutes biked compared to casual riders. In June, there was only a slight lead in total minutes (50.27% for members vs 49.73% for casual riders).

### Average Ride Duration

June casual rides are 140% longer than member rides on average. However, that difference decreased to just 39.73% in December.

### Distance Covered

In June, there were 85,105 miles ridden. Members accounted for 68.15% of those miles. In December, 40,202 miles were biked, and members’ share increased to 80.45% despite fewer total riding minutes.

### Electric vs. Pedal

Riders favored using electric bikes more than 2 to 1 in December, whereas, in June, the preference was only 15% greater. Per the [How it Works](https://citibikenyc.com/how-it-works) page, there are 25,000 bikes available for use. With less riders in December would be likliehood of greater access to the the e-bikes as preference to get where you want to go easier than traditional pedal bikes. Greater access and colder temperatures are most likely reason for the increase in e-bike percentage in December.

### Possible Insights

- **Commuters vs. Leisure Riders**: Given the downtown terrain, the use of the bikes as an alternative mode of transportion to mass transit and for shorter rides, frequent trips (e.g., commuting), while casual riders might use bikes for longer, recreational trips. This is supported by the June data, where casual ride durations were more than twice as long as member rides. The casual segment appears to reduce activity in colder weather.
- **Loyal User Base**: There appears to be strong engagement among a loyal member base. It was expected to see reduced activity from June to December however members took more individual trips and rode for more miles in December than casual users did in June despite their minutes biked being less than half that of casual riders in June.
- **What Time are people riding**: Our map comparison shows that the majority of bike activity takes place between Jersey City(Downtown) and (Uptown) Hoboken areas. Applying a time of day filter to the June and December maps show that the majority of rides take place after 12 PM daily, approximately 2 to 1 for each month.
