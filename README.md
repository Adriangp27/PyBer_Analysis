# PyBer_Analysis
## Project Overview
Among the two sets of data, city and ride, Pyber, a ride sharing company, requires a deep look. In order to create data-driven decisions, it is imperative to visualize the provided data using the Pandas library, Matplotlib, and Jupyter Notebook. Here is a list of deliverables according to the company's requirements.

1. Loading, reading and inspecting the dataset
2. Merging datasets to create a workable dataframe
3. Calculating the total rides, drivers, and the amount of fares for each city type
4. Calculating the average fare per ride for each city type
5. Calculating the average fare per driver for each city type
6. Creating a Pyber Summary Dataframe
7. Plot line chart analysis from the created Pyber Dataframe to show the differences in fares per city

## Resources
-Data Source: city_data.csv, ride_data.csv
-Software: Python 3.9.7, Anaconda 2020.11, Jupyter Notebook 6.4.5

## Results
### Rural

125 rides
78 Total Drivers
$4,327.93 Total Fares
$34.62 Average Fare per Ride
$55.49 Average Fare per Driver

### Suburban

625 rides
490 Total Drivers
$19,356.33 Total Fares
$30.97 Average Fare per Ride
$39.50 Average Fare per Driver

### Urban

1,625 rides
2,405 Total Drivers
$39,3854.38 Total Fares
$24.53 Average Fare per Ride
$16.57 Average Fare per Driver


![Pyber_fare_summary](https://user-images.githubusercontent.com/99752443/162572877-29269872-f266-42c7-bf65-a80aec4fcee2.png)
![Fig1](https://user-images.githubusercontent.com/99752443/162572906-a77fa355-365c-4d66-9aca-65ba29ca5bb6.png)
![Fig2](https://user-images.githubusercontent.com/99752443/162572907-c51ab7f1-6f6d-4f99-a195-eafaa80129f9.png)
![Fig3](https://user-images.githubusercontent.com/99752443/162572917-7882180e-247d-4b80-a38e-ce68350deb9a.png)
![Fig4](https://user-images.githubusercontent.com/99752443/162572919-c53abdbb-b7d4-475b-bc00-8bd7eec56b6f.png)
![Fig5](https://user-images.githubusercontent.com/99752443/162572921-05fdc267-9784-4fa0-b0c7-e984b57d0e75.png)

In light of the current summary and the fare trends this indicates that the urban markets have the higher number of rides, while the rural markers have the lowest number. As shown in the pie chart below, this is also reflected in the percentage of fares by each city type. Rural markets may have the fewer rides, but their average fares are the highest, because rural customers are generally travelling a greater distance than their urban and suburban counterparts. Additionally, the number of drivers reflects the demand for each city type, especially in urban markets with more drivers than rides.

## Recommendations
* As there are more drivers than is needed in the urban market, rural and suburban drivers should be moved to the urban market. 
* Despite only accounting for 2.6% of all drivers, the rural market accounts for 6.8% of the total fares.
* A higher average fare per city type will increase demand in rural areas.
* Analyzing the cause of the significant downturn during the third week of February
* To gain a deeper understanding of differences in average fares and rides between different cities, including the average miles traveled per ride in the dataset.
