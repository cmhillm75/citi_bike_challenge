# citi_bike_challenge

Tableau Module 18. I chose to use a summer vs winter comparison of citi_bike data. My `Resources` folder contains the original downloads `JC-202406-citibike-tripdata.csv` and `JC-20412-citibike-tripdata.csv`. I used Jupyter Notebook, created 2 DataFrames, and added 2 columns of information: "trip_distance_miles" and "trip_duration_min". I then saved the updated CSV files as `june_bike.csv` and `december_bike.csv`.

## Links

[Citi Bike page](https://citibikenyc.com/system-data)

[citi_bike_story](https://public.tableau.com/views/citi_bike_story_17398497522060/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

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

Members take significantly more rides than casual riders. The member share of rides was 9.64% greater in December than in June. The significant decrease in casual rides in December is easily explainable by temperature changes. Members are more likely using bikes for transportation versus leisure.

### Total Time

In December, members accounted for more than 3 times the amount of minutes biked compared to casual riders. In June, there was only a slight lead in total minutes (50.27% for members vs 49.73% for casual riders).

### Average Ride Duration

June casual rides are 140% longer than member rides on average. However, that difference decreased to just 39.73% in December.

### Distance Covered

In June, there were 85,105 miles ridden. Members accounted for 68.15% of those miles. In December, 40,202 miles were biked, and members’ share increased to 80.45% despite fewer total riding minutes.

### Electric vs. Pedal

Riders favored using electric bikes more than 2 to 1 in December, whereas, in June, the preference was only 15% greater. This suggests that, especially in colder months, electric bikes are preferred. When comparing December to June, the transportation usage by members is supported.

### Possible Insights

- **Commuters vs. Leisure Riders**: Members might primarily use bikes for shorter, frequent trips (e.g., commuting), while casual riders might use bikes for longer, recreational trips. This is supported by the June data, where casual ride durations were more than twice as long as member rides. The casual segment appears to reduce activity in colder weather.
- **Loyal User Base**: There appears to be strong engagement among members, suggesting a loyal user base. Our map comparison shows that the majority of bike activity takes place in Jersey City and Hoboken areas.
