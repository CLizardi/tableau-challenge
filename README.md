# Insights into Citi Bike Ridership in Jersey City - Citi Bike Analytic

![citibike](https://user-images.githubusercontent.com/52866379/236699372-a33ddf2e-9697-46fa-b67b-33f75cbe8f5d.png)

# Dashboards
These dashboard's were created to provide a comprehensive view of the ridership patterns and preferences of Citi Bike users in Jersey City. The dashboard was created using Tableau, a powerful data visualization tool, and provides a variety of visualizations that allow users to explore different aspects of the Citi Bike program, including user analysis, station analysis, and geographic analysis. 

The dashboards were designed to be user-friendly and interactive, allowing users to filter the data based on different criteria, such as user type, gender, and age. The visualizations in the dashboards are also designed to be visually appealing and easy to understand, making it easy for users to gain insights into the data without needing to have a deep understanding of data analysis or statistics.

This is a valuable resource for bike share program managers and city planners who are looking to make informed decisions about the allocation of resources, pricing strategies, and infrastructure improvements for the Citi Bike program. By providing insights into the ridership patterns and preferences of Citi Bike users, the dashboard can help bike share program managers and city planners make informed decisions that will improve the overall experience of Citi Bike users and promote the growth and sustainability of the bike share program.

![Dashboard 1](https://user-images.githubusercontent.com/52866379/236699374-8d0b3019-5f3d-412e-958a-2fd89f835fce.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/CitiBikeVisualization_16834855967760/Dashboard1?publish=yes

![Dashboard 2](https://user-images.githubusercontent.com/52866379/236699375-2171bb6e-f555-4f04-975a-ea7222ceed7f.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/CitiBikeVisualization2_16834856479180/Dashboard2?publish=yes

# User Analysis
The User Analysis section provides a comprehensive view of the Citi Bike ridership patterns, helping to inform decision-making related to the allocation of resources, pricing strategies, and infrastructure improvements. By understanding the demographics and behaviors of Citi Bike riders, bike share program managers and city planners can make informed decisions that will help to promote the growth and sustainability of the bike share program.e. 

## Start/End Time for User Types Line Graph
This visualization shows the distribution of bike trips by user type (subscriber vs. customer) over the course of a day. By using different colors to represent the two user types, we can see that subscribers tend to use the bike share program more heavily during peak commuting hours, while customers tend to use the program during off-peak hours and on weekends.

![Start Time](https://user-images.githubusercontent.com/52866379/236699383-44994d9b-61cb-4785-b757-379e970e5806.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/StartTime/StartTime

![End Time](https://user-images.githubusercontent.com/52866379/236699378-b06b04d2-f4b8-4a04-afff-dc96ede29c40.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/EndTime/EndTime

## User Types vs. Average Trip Duration Bar Graph
This visualization shows the average duration of bike trips for subscribers and customers. By using different colors to represent the two user types, we can see that customers tend to take longer trips than subscribers, which may reflect differences in how the two groups use the bike share program.

![User Type vs  Average Trip Duration](https://user-images.githubusercontent.com/52866379/236699387-8f6020af-d0f5-478a-b56c-ccf6d46465b2.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/UserTypevs_AverageTripDuration/UserTypevs_AverageTripDuration

## Average Trip Duration by Gender Bar Graph
This visualization shows the average duration of bike trips by gender. By using different colors to represent male and female riders, we can see that female riders tend to take longer trips than male riders. This information can be useful for bike share program managers and city planners who are looking to target specific populations with bike share promotions or infrastructure improvements. 

In the Citi Bike dataset used for this project, gender is represented by the numbers 0, 1, and 2. According to the Citi Bike data documentation, gender is coded as follows:

0: Unknown
1: Male
2: Female

![Trip Duration Vs Gender](https://user-images.githubusercontent.com/52866379/236699386-1504c105-7c17-4c33-9477-6884b79475f6.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/TripDurationVsGender/TripDurationVsGender

## Duration of Bike Trips and Age Line Graph
This visualization shows the relationship between the age of bike trip riders and the duration of their trips. By showcasing different ages, we can see that older riders tend to take longer trips than younger riders. This information can be useful for bike share program managers and city planners who are looking to optimize the system for different age groups, potentially by offering different pricing plans or incentives to encourage more frequent use among older riders.

![Duration of bike trips and age](https://user-images.githubusercontent.com/52866379/236699376-10b22a79-45d0-4fb4-ba5a-3ddbf4497b43.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/Durationofbiketripsandage/Durationofbiketripsandage

# Station Analysis

Understanding the starting and ending stations of each Citi Bike trip is an important aspect of analyzing ridership patterns and demand for bike sharing services. By focusing on the stations with at least 1000 entries, the Station Analysis section of the dashboard provides valuable insights into the most heavily used stations in Jersey City.

These visualizations can help bike share program managers and city planners make informed decisions about where to allocate resources and how to improve the program to better meet the needs of riders. By identifying the most popular bike trip starting and ending points, they can ensure that there are enough bikes, bike docks, and infrastructure in these areas to meet the demand.

Overall, the Station Analysis section provides a comprehensive view of the ridership patterns and preferences of Citi Bike users in Jersey City, which can be useful for city planners and bike share program managers who are looking to make data-driven decisions about the program.

## Most Popular Start Stations

![Start Stations (At Least 1000 Entries)](https://user-images.githubusercontent.com/52866379/236699381-9cfa69c7-131c-44a0-a578-1ef47d3f03ad.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/StartStationsAtLeast1000Entries/StartStationsAtLeast1000Entries

## Most Popular End Stations

![End Stations (At Least 1000 Entries)](https://user-images.githubusercontent.com/52866379/236699377-9bc84779-609c-4e87-9397-3a786b3317d3.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/EndStationsAtLeast1000Entries/EndStationsAtLeast1000Entries

## Start Station Names vs. Number of Records

The Start Station Names vs. Number of Records visualization is a bar chart that displays the number of trips that started at each Citi Bike station with at least 1000 entries. This visualization is useful for gaining insights into the popularity of different Citi Bike stations and the ridership patterns at these stations. The bar chart shows that there are several stations that have a much higher number of trips than others, such as Grove St PATH, Hamilton Park, Exchange Plance, and Newport Path. These stations may be important hubs for the Citi Bike program, and understanding the ridership patterns at these stations can help bike share program managers and city planners make informed decisions about where to allocate resources and how to improve the program. Overrall, this visualization provides a useful summary of the ridership patterns at different Citi Bike stations, helping bike share program managers and city planners make informed decisions to improve the program and meet the needs of riders.

![Start Popular](https://user-images.githubusercontent.com/52866379/236699380-e570aec8-ad93-47e6-9a00-3066f8edd10b.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/StartPopular/StartPopular

# Geographic Analysis

This visualization shows the geographic distribution of bike trips in Jersey City by mapping the starting and ending stations of each trip. By using different colors to represent the starting and ending stations, we can see that bike trips are concentrated in certain areas of the city, such as downtown and along the Hudson River waterfront.

![Starting Locations_Stations](https://user-images.githubusercontent.com/52866379/236699385-10fb8e25-a94e-47a2-9af1-a4a82aeb3a3e.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/StartingLocationsStations/StartingLocationsStations

![Ending Locations_Stations](https://user-images.githubusercontent.com/52866379/236699379-7e9c020b-c135-47a6-be7c-c3c1a802ee90.png)
https://public.tableau.com/app/profile/christian.lizardi/viz/EndingLocationsStations/EndingLocationsStations

# Conclusion
These dashboards provide a comprehensive view of the ridership patterns and preferences of Citi Bike users in Jersey City. By analyzing and visualizing data related to user types, gender, age, station usage, and trip duration, we can gain valuable insights into the behaviors and preferences of Citi Bike users.

The dashboards were created using Tableau, a powerful data visualization tool that allowed for the creation of visually appealing and user-friendly visualizations. Through the creation of this dashboard, I learned how to effectively use Tableau to visualize complex datasets and communicate insights to stakeholders.

Overall, the Tableau dashboards presents a valuable resource for bike share program managers, city planners, and other stakeholders who are looking to make informed decisions about the Citi Bike program. By providing insights into the ridership patterns and preferences of Citi Bike users, the dashboard can help improve the overall experience of Citi Bike users and promote the growth and sustainability of the bike share program.

