# CitiBike-Tableau

![CitiBikes](citi-bike-station-bikes.jpg)

**Background**

CitiBike is the nation's largest public bicycle sharing system serving New York City. The Citi Bike program  was launched in May 2013, and has become a vital part of the vast transportation system in NYC.It radically changed people's mobility for the better, providing a reliable means for millions to explore the city. Citi Bike offers efficiency, affordability, and contributes to a healthier environment.

Citi Bikes are available for use 24 hours/day, 7 days/week, 365 days/year with hundreds of stations across NYC, Jersery City, and Hoboken. The program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. 

**Task**

 1. Aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
 2. Develop a comprehensive visualization strategy to answer the following key questions about Citi Bike usage:

    i. User Behavior: How does membership status impact usage patterns?

    ii. Station Performance: Identify top and bottom-performing stations and explore potential causes for variations.

    iii. Spatial Patterns: Analyze the geographic distribution of Citi Bike trips and identify usage hotspots.

    iv. Temporal Trends: Understand how usage patterns evolve over time (e.g., daily, weekly, seasonal).

 3. Design a dashboard and provide analysis for the occuring phenomenon.
 4. Create at least one map visualization.
 5. Create a focused, concise, easy to understand, and visually compelling Tableau story that will inform programmatic changes to city officials, pulic administrators and heads of New York City municipal departments.

**Tools/Languages Used**

- Juypter Notebook
- Python
- Pandas
- Tableau

 **ETL process**

 The data was downloaded from [CitiBikes website](https://citibikenyc.com/system-data).The data includes:

    - Ride_ID: A unique identifier for each ride.
    - Rideable_type:Type of bike used for the ride.
    - Started_at: Date and start time of the ride.
    - Ended_at: Date and end time of the ride.
    - Start_station_name: Name of station where ride started.
    - Start_station_ID: Unique ID for the start station
    - End_station_name: Name of the station where ride ended.
    - End_station_ID: Unique ID of the end station.
    - Start_latitude: The latitude coordinate of the start station.
    - Start_longitude: The longitude coordinate of the start station.
    - End_latitude: The latitude coordinate of the end station.
    - End_Longitude: The longitude coordinate of the end station.
    - Member_casual: Indicates whether the rider is a member(subscriber) or a casual(non-subscriber) user of CitiBikes program. 

![citibike data](<Screenshot 2024-07-09 013735.png>)

**Visualizations**

https://public.tableau.com/app/profile/lynda.sempele/viz/citibike_2024_analysis/NJCitiBikeStoryboard?publish=yes

**Analysis**
**CitiBike Trends in New Jersey (Q1 2024)**

User Analysis:

- High Membership Rate: A strong majority (nearly 80%) of CitiBike users leverage memberships, suggesting a committed user base.
- Growing Ridership: Bike usage shows a positive trend from January to April, indicating increasing program adoption. This could also be attributed to weather getting warmer, thus increased bike usage. Notably, electric bikes are the most popular choice among riders.
- Peak Commute Times: The line graph reveals peak usage times at 8am and 5pm, aligning with typical commuting hours.


Station Analysis:

Hoboken Terminal and Grove Street PATH stations emerge as the most frequented starting and ending points for Citi Bike trips. This indicates strong demand and potential opportunities for further bike share expansion in the area. Conversely, several stations exhibit exceptionally low ridership, warranting a deeper investigation into underlying factors such as station location, accessibility, bike availability, and surrounding amenities. Addressing these issues could optimize station utilization and enhance the overall Citi Bike experience.

Map Analysis:

The maps illustrate the geographic distribution of Citi Bike usage, highlighting Hoboken Terminal and Grove Street PATH as the most popular stations.


**References**

Citi Bike NYC (n.d.). Citi Bike System Data. https://citibikenyc.com/system-data